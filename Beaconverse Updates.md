# Beaconverse Updates 

![](https://i.imgur.com/GXaWVtM.jpg)

In this document, you will find an extensive collection of information regarding the Ethereum & Gnosis Beacon Chain, including daily updates on client developments, insightful commentary from the development team, practical advice for validators, and a variety of useful tools. Whether you're a pleb user or just getting started, this document serves as an indispensable resource for all things related to the Ethereum & Gnosis Beacon Chain.


:::info
:bulb: This document is under development. Last update: Feb, 2

**Find this document incomplete? Leave a comment!**
:::

### Table of Contents
* [What is Beacon Chain?](https://hackmd.io/L_vqTNA8QcKBlL-_JiNXTw?view#WTF-Beaconchain-%F0%9F%90%BC) 
* [Client Updates](https://hackmd.io/L_vqTNA8QcKBlL-_JiNXTw?view#Clients-Updates)
  * Execution Layer
  * Consensus Layer
  * Client Diversity 
* [Devs Updates](https://hackmd.io/L_vqTNA8QcKBlL-_JiNXTw?view#Devs-Updates)
  * Ethereum AllCoreDev
  * Gnosis Core Devs Call 
* [Validator Updates](https://hackmd.io/L_vqTNA8QcKBlL-_JiNXTw?view#Validator-Updates)
  * Solo Staker
  * LSD
  * DVT
* [Meetup/Community Call/Event](https://hackmd.io/L_vqTNA8QcKBlL-_JiNXTw?view#MeetupCommunity-CallEvent)
  * Upcoming
  * Past
* [Awesome Tools](https://hackmd.io/L_vqTNA8QcKBlL-_JiNXTw?view#Awesome-Tools)
  * Analytics
  * Validator Tools
  * Resources

## What is Beacon Chain?
The Beacon Chain was the name of the original proof-of-stake blockchain that was launched in 2020. It was created to ensure the proof-of-stake consensus logic was sound and sustainable before enabling it on Ethereum Mainnet. Therefore, it ran alongside the original proof-of-work Ethereum. Switching off proof-of-work and switching on proof-of-stake on Ethereum required instructing the Beacon Chain to accept transactions from the original Ethereum chain, bundle them into blocks and then organize them into a blockchain using a proof-of-stake based consensus mechanism. At the same moment, the original Ethereum clients turned off their mining, block propagation and consensus logic, handing that all over to the Beacon Chain.[*](https://ethereum.org/en/upgrades/beacon-chain/#what-is-the-beacon-chain) 

### Timeline - Ethereum

- [x] The Beacon Chain shipped on December 1, 2020
- [x] Bellatrix Hard-Fork September 6, 2022
- [x] Paris Hard-Fork September 14, 2022
- [x] The Merge September 15, 2022

![](https://i.imgur.com/ReBVtnM.png)

### Timeline - Gnosis Chain

- [x] The Beacon Chain shipped on December 8, 2021
- [x] Bellatrix Hard-Fork November 30, 2022
- [x] The Merge December 8, 2022



Gnosis runs the same client software as Ethereum, with minor parameter tweaks. As such, Gnosis is a Proof-of-Stake network that uses Ethereum's Beacon Chain consensus.

#### [HAPPY MERGE EVERYONE 🐼👉👈🐼 ](https://twitter.com/gnosischain/status/1600925552575418369)

## Clients Updates

* **Execution Layer Updates**
    * [Geth](https://geth.ethereum.org/)
      * [v1.10.26](https://t.co/kfu1S85afy) Nov 3, 2022
    * [Nethermind](http://nethermind.io/)
      * [v1.16.1 ](https://github.com/NethermindEth/nethermind/releases/tag/1.16.1) Jan 25, 2023
    * [Erigon](https://github.com/ledgerwatch/erigon#erigon)
      * [v2.37.0 ](https://github.com/ledgerwatch/erigon/releases/tag/v2.37.0) Jan 29, 2023
    * [Besu](https://hyperledger.org/use/besu) No updates
    * [Reth](https://github.com/paradigmxyz/reth) Pre-Alpha
    * [Silkworm](https://github.com/torquem-ch/silkworm#about-silkworm) Pre-Alpha


* **Consensus Layer**
    * [Lodestar](https://lodestar.chainsafe.io/)
      * [v1.4.0](https://blog.chainsafe.io/lodestar-v1-4-0-release-and-a-look-ahead-8f0a99c2e708) Jan 31, 2023 
    * [Teku](https://consensys.net/knowledge-base/ethereum-2/teku/)
      * [v23.1.0](https://github.com/ConsenSys/teku/releases/tag/23.1.0) Jan 26, 2023
    * [Prysm](https://prysmaticlabs.com/)
      * [v3.2.0](https://t.co/eD2lW1ekcw) Dec 16,2022
    * [Nimbus](https://nimbus.team/)
      * [v23.1.1](https://github.com/status-im/nimbus-eth2/releases/tag/v23.1.1) Jan 26, 2023
      * [Design notes for decoupled EIP4844](https://github.com/status-im/nimbus-eth2/pull/4550)
    * [Lighthouse](https://lighthouse.sigmaprime.io/)
      * [v.3.4.0](https://t.co/dYmUBaqQEF) Jan, 12, 2023

:::danger 

🚨Check 👉 [Client Diversity](https://clientdiversity.org/)🚨

:::

:::info

**Client Diversity Is Not Optional - It's critical**

Many know client diversity is important for a more resilient network, but they don't understand why or just how essential it is. It's not only important — **it's critical**  
:::


## Core Devs Updates

* **Gnosis Core Devs Call** - Feb 1, 2023
    * [Notes](https://www.gnosis.io/blog/gnosis-core-devs-call-notes-february-1-2023)
    * [Video](https://t.co/cyoYw5PHi1)
 * **Ethereum AllCoreDevs** - Jan 19, 2023
    * [Notes](https://github.com/ethereum/pm/issues/704)
    * [Video](https://t.co/PQdERTjEjW)
  



## Validator Updates

* **Solo Stakers**
  * [ETH Withdrawals FAQ](https://notes.ethereum.org/@launchpad/withdrawals-faq)
  * [Ethereum Withdrawal Call Series](https://www.youtube.com/watch?v=dGGMNYbWnP4)
  * [🍄Stereum - Ethereum Node - "2.0.0-rc.12" Release 🍄](https://github.com/stereum-dev/ethereum-node/releases/tag/v2.0.0-rc.12)
  * [Ethereum's first public #withdrawal testnet is live 🔥](https://t.co/fZ6ogRjeZY)
  * [ethstaker.tax now supports execution layer income](https://www.reddit.com/r/ethstaker/comments/10p0bum/ethstakertax_news/)
  * [First withdrawal testnet explorer is also available on Beaconcha_in](https://twitter.com/beaconcha_in/status/1620552738382946304)

 * **LSD**
    * [RocketPool](https://rocketpool.net/)
      * [Reached 2000 permissionless node operator ](https://twitter.com/Rocket_Pool/status/1618497490894065664)
      * [Hudson Sets Up A Rocket Pool Node!](https://www.youtube.com/watch?v=qINfnVPSQ1U)
      * [Index Coop Diversified Staked ETH Index ($dsETH) ](https://twitter.com/indexcoop/status/1618297181928321025)
      
    * [Lido](https://lido.fi/)
      * [Aave v3 Integration](https://twitter.com/LidoFinance/status/1618902851958501376)
      * [Lido Grants](https://t.co/wyYkOWFEas)
  * **DVT**
    *  [SSV](https://ssv.network/) 
       * [SSV node: Shifu V2 🎉](https://blog.ssv.network/get-ready-for-shifu-v2-multi-duty-feb-2023-5166753a2c94) 
      * [Obol](https://obol.tech/)
         * [Ambassador Program](https://www.notion.so/Obol-Ambassador-Program-52ee03cb655c4da4ad2814f93bb21a93)
         * [Bia Testnet](https://blog.obol.tech/the-bia-testnet-obol-ambassador-program/)
     * [Diva](https://divalabs.medium.com/here-comes-the-diva-liquid-staking-powered-by-distributed-validators-9e5c3bd38896) 
       * [Releasing first set of docs](https://t.co/VCetdcu6cX)
     * [Stader Labs](https://twitter.com/staderlabs_eth)

 

## Meetup/Community Call/Event

### Upcoming 
* Feb 2 AllCoreDev Call

### Past
* [Gnosis Validator Meetup with Nethermind](https://www.youtube.com/watch?v=P7nuPNZZjJQ)
* [Jan 31 :  EthStaker community withdrawals call](https://www.reddit.com/r/ethstaker/comments/10p3uen/ethstaker_community_withdrawals_call_january_31/)
* [Feb 1 :  Gnosis Ecosystem Wednesday with Beaconcha.in](https://discord.gg/nTK23HqK?event=1068254375832715315)
* [Feb 1 Gnosis Core Devs Call ](https://www.youtube.com/watch?v=NxPWQLd8H7g)

## Awesome Tools

### Analytics

* [ETH Deposits to Beacon Chain Stats](https://dune.com/LidoAnalytical/eth-deposits-stats)
* [ETH2 Staking](https://dune.com/hildobby/eth2-staking)
* Beaconchain Explorer 
  * [Mainnet](https://beacon.gnosischain.com/)
  * [Gnosis](https://beacon.gnosischain.com/)
* [Etherscan](https://etherscan.io/)
* [EtherNodes](https://ethernodes.org/)
* [Migalabs](https://migalabs.es/crawler/dashboard)


### Tools for validators

* [Ethereum On Arm](https://ethereum-on-arm-documentation.readthedocs.io/)
* [EthDocker](https://eth-docker.net/)
* [Ethwizard](https://github.com/stake-house/eth-wizard)
* [Stereum](https://stereum.net/)
* [DappNode](https://dappnode.com/)
* [Avado](https://ava.do/)

### Resources

* [Awesome Ethereum Staking Resources](https://hackmd.io/qSzUlW7qQ-WD95H7bbmMcw?both)
* [EthStaker knowledge base](https://github.com/eth-educators/ethstaker-knowledgebase)
* [Gnosis Chain Staking Guide & Shapella (Shanghai + Capella) Upgrade](https://gnosisvalidator.substack.com/p/the-shanghai-upgrade-and-gnosis-chain)



---

Thank you! You can find me on

👉[GitHub](https://github.com/0xarmagan)
👉[Twitter](https://twitter.com/0xarmagan)
👉[Telegram ](https://t.me/armaganercan)







