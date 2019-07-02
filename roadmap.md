# Roadmap
## Roadmap Updates

https://github.com/bismuthfoundation/Roadmap

## September 2018 Roadmap Update

![img](https://bismuth.cz/wp-content/uploads/2018/09/roadmap.jpg "roadmap")

## February 2018 Roadmap Update

### Accessibility

#### Codebase modularity and objects ✔

Whilst working towards improving Bismuth over the last few months it has become obvious to the developement team that a refactoring of the code is needed to make it easier and more accessible to other developers. Teams and individuals have contacted us, interested in participating and helping the project move forward, but have not been sure where to start. Therefore a process of refactoring the Bismuth codebase into individual modules and the creation of standard objects is already in progress (currently peer handling and configuration). This is seen as one of the main steps needed to help with the onboarding of new participants.

#### Exchange compatibility ✔
One of the drawbacks of a completely new system is compatibility with the existing infrastructure, preventing Bismuth to be easily integrated across standard exchanges. For this purpose, a Bitcoin-standard remote procedure call (RPC) module is under development, close to be finished. This will allow exchanges to add Bismuth just as easily as any Bitcoin derivates on the market.

### Improvements

#### Tiered mempool ✔
One of the most important issues was a complex redesign of the mempool system. Bismuth is now the first platform that offers a so-called tiered mempool. Each node has a specific set of rules for certain types of transactions, assuring that it does not become clogged from a malicious intent, without an increased fee pressure on the end-user. This code will be further improved to be programmable and adaptable.

#### Graphics ✔
With the growing popularity of the platform, we have been receiving new graphics suggestions recently, regarding logo and the overall design. Some of the artwork is coming from the professional artists. However, timeline for implementation remains uncertain.

### Newly added features

#### Transaction Identification Standardization ✔
A standard TXID system has been specified for Bismuth. It consists of the first 56 symbols of a transaction signature. This system has been added to the http://bismuth.online explorer and should help exchanges identify potential problems with withdrawals, deposits and transactions in general.

#### Migration to true numeric representation ✔
During testing, several issues have been identified around the current float calculation model, especially the requirement of users to keep a very small (dust) amount in the account when attempting to spend all coins under certain conditions. The wallet has already been fully converted to an improved Python decimals module, the rest of the system will follow shortly.

Future features, development and research

#### URL with checksum ✔
Bismuth will support a transaction URL system. This will allow users to send and receive transactions fully defined in a single entry, including a checksum to make sure no alterations are possible (i.e. inclusion of an invalid character or a blank space to the recipient address). This feature will synergize with the general progress towards a syntax standardization and programmability.

#### Google Protocol Buffers ✔
Although serialization and networking have undergone serious improvements over Bismuth’s history, it is still not optimal. Residual parts from Python 2.7 and the old database typing cause blocks and mempool to use larger bandwidth than necessary. Google Protocol Buffers offer a good remediation, with a top class serialization techniques, saving multitudes on bandwidth in testing, natively in Python. Implementation for Bismuth is underway.

#### Hashwork concept ✔
This feature is an optimization to the current longest-chain rule used in Bismuth blockchain synchronization and consensus determination. In case of a chain split, or a so-called fork, a difficulty drop is capable of producing a longer chain with lower difficulty under certain circumstances. To better secure the network, rules can be modified to include elements of hashrate and blocktime in order to help determine the chain with the most work put into it, the essential principle of all Proof of Work systems.

#### Multiple Address Support ✔
While users can currently watch other addresses directly from the wallet, it is still not possible to operate multiple addresses from it. Concept code is now finished for the multiple address support and integration can begin.

#### Masternodes ✔
Community discussion led to a realization that the current Bismuth OpenField technology (arbitrary data inclusion) can support minting delegation for masternodes. Offline minting is realistically possible with this concept. Rights of the future masternodes have been extended with transaction signing to secure the network not only though network prioritization, but through block creation itself. ETA for masternodes is still unspecified within a scope of 2018.

#### HTML wallet and cold storage ✔
A project called BISafe is currently being developed and it includes an HTML Bismuth wallet for mobile support, skin usage and easy translations. An offline address generator is a part of this project.

### November 2017 Roadmap Update

Since September, Bismuth has attracted more talented developers than in all of its previous months combined. They have provided valuable contributions to the codebase and developed new platforms, like the public GPU pool, which is going to open this week. Issuance of tokens is now available to the wide public and will serve as an operating layer for the smart contracts, for which the syntax will be formulated first. In the past weeks, Bismuth development has been most focused around improvements to the underlaying codebase, including difficulty tuning, database optimizations, security subsystem implementation and wallet streamlining. The old and heavy local wallet has been switched to a light version of it, which can either operate locally or with other nodes, while only utilizing node commands. This is a basic step towards accepting mobile and third-party wallets and also enabling node-level communication for third-party applications, like for example the backend of heatnodes.org. Also, we are now able to start the development of a custom masternode implementation, although this is still in the proof of concept stage. Block 400,000 marks an important security update, which also adds a new difficulty calculation based on actual network hashrate. Bismuth now also offers an official node map in the public repository, which you can view here or run your own. So besides the previous goals, there is one new now:

- Technology to incentivize long-term holders and node hosts with additional rewards  (masternodes)
### September 2017 Roadmap Update

With Bismuth now having most of the May 2017 Roadmap implemented, it is time to declare new goals based on the long-term vision of constant development and improvements. Besides the described achievements, the Bismuth core code has also been strengthened, block security has been greatly increased with the recent successful hard forks. Automatic bootstrapping is now in place for user convenience together with partial rework of the user interface and a handy addition of wallet backup and other capabilities. During the last month’s research, it has become obvious that the unique interpretation engine scheme Bismuth is using for its selective decentralized application execution and operation could be extended with a standard module for execution of decentralized contracts in a dedicated new module. The first and necessary application will be an addition of a second-layer decentralized token platform, granting users an innate ability to issue, exchange and manage tokens on the Bismuth platform. In the creation of the first secondary currency, the first rules for token operation will be defined, giving Bismuth the basis for an industry standard, executable smart contract dimension. To shortly list the next goals:

- Additional decentralized token layer ✔
- Token syntax and command standardization as a base layer for decentralized contract mechanics ✔
- Decentralized contracts execution platform with a common shared state hooked to Bismuth through OpenField

### May 2017 Roadmap

I would like to inform you that the launch of Bismuth has been successful beyond expectations. In the first two weeks, I have upgraded the mining algorithm to handle unlimited amount of users, improved support for Linux users, secured and bootstrapped the core and added numerous new features under the hood. We are now slowly approaching the stage of the light client support with the latest versions. Work on a mining pool have been restored and are in negotiation with external programmers. As for the forseeable future, you will see the following:

- Restructured mining difficulty drop mechanics ✔
- Full messaging support for both encrypted and unencrypted messages ✔
- Ability to symmetrically and asymmetrically encrypt any data on the blockchain ✔
- Implementation of the blockchain-secured legal document storage (footprints and full documents)
- Decentralized HTML browsing capabilities with direct evaluation ✔
- The first ever decentralized performance and availability monitoring tool for servers (partially implemented)
- The mining pool ✔
- The development does not end with the last point, but these are mid-term realistic goals. As for the distant future, I would like Bismuth to stay on the cutting edge of technology, supporting blockchain-based IoT for which I already have the case study. Bismuth is also capable of supporting an asset exchange and should be able to provide a basis for the artificial intelligence and deep learning infrastructures with connection to the real world. There is a plenty to look ahead for.

