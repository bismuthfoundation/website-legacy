# Projects

## Current projects

### Bismuth Node
The backbone of the entire Bismuth network, maintains the blockchain and processes all transactions. In a decentralized system, every node processes data independently and running a node supports the network.

- Link to source: https://github.com/hclivess/Bismuth/blob/master/node.py
- Link to installer: https://github.com/hclivess/Bismuth/releases

### BismuthTools Web Edition
Software written by Ian McEvoy that enables access to the entire blockchain. Starting with a summary page of recent transactions, ledger query for transactions, accounts, block numbers, hashes, miner statistics, rich list, sponsorships handled though Opengraph, API and charts.

- Link to service: https://bismuth.online
- Link to source: https://github.com/maccaspacca/BismuthToolsWeb

### Bismuth Tools Desktop Edition
Uses information from the bismuthtoolsweb api to display Bismuth cryptocurrency explorer information. Run from Bismuth installation folder and it will use local wallet information automatically. Run from any other folder and it will use wallet information and explorer API from the address in tools.ini config file.

- Link to source: https://github.com/maccaspacca/DesktopTools

### Bundled Transaction Explorer
This transaction explorer is bundled with every Bismuth distribution and provides a basic overview of the recent transactions with statistical summary of blockchain thoughput and a simple interactive chart.

- Redirect link: https://bismuth.cz/explorer
- Link to service: http://bismuth.live:5492/
- Link to source: https://github.com/hclivess/Bismuth/blob/master/ledger_explorer.py

###  Bismuth Bundled Wallet
This is the main wallet everyone is supposed to use for basic Bismuth usage, supports key encryption, token operations, alias operations, signing, secure messaging and interaction with decentralized applications on the Bismuth blockchain. Every Windows user has this wallet included with the installer.

- Link to source: https://github.com/hclivess/Bismuth/blob/master/wallet.py
- Link to installer: https://github.com/hclivess/Bismuth/releases

### Nonce GPU Mining Pool
- Link to service: http://www.noncepool.com

### Coinsaurus GPU Mining Pool
- Link to service: https://bismuth.coinsaurus.com

### ACC GPU Mining Pool
Developed by Euroline, one of the first Bismuth mining pools, includes download links to a proprietary miner.

- Link to service: https://bismuth.acc-pool.pw

### BIS-Pool GPU Mining
- Link to service: https://bis-pool.io

### EggPool GPU Mining
Pool developed by EggdraSyl, member of the Bismuth Foundation.

- Link to service: http://eggpool.net
- Link to support: http://eggpool.net/?action=help_faq 

### Bismuth RPC
A python json-rpc server that will allow to interact with a Bismuth node like we do with bitcoind. Will ease integration of Bismuth with exchanges and pools.

- Link to source: https://github.com/EggPool/BismuthRPC

### Heatnodes
A selection of extensive Bismuth service offering its own transaction and account explorer, network and difficulty charts, rotating globe with nodes.

Link to service: https://heatnodes.org/?page_id=859

### BISafe
A safe, HTML wallet for Bismuth Cryptocurrency.

Link to source: https://github.com/EggPool/BISafe

### Offline Address Generator
A Safe (offline) Bismuth address generator to make your cold wallet.

Link to source: https://github.com/EggPool/BISafe/tree/master/Generator

### BismuthAPI
API Doc and code samples for Bismuth cryptocurrency.

Link to source: https://github.com/EggPool/BismuthAPI

### Bismuth Paper Wallet
Paper wallet creator for Bismuth, currently in testing phase.

Link to source: https://github.com/maccaspacca/Bismuth-Paper-Wallet

### Bismuth Faucet
A reference faucet for the Bismuth cryptocurrency. The application consists of two parts – a main faucet application and a payment processing module.

Link to source: https://github.com/maccaspacca/faucet

### ZircoDice Casino
A simple decentralized betting application running in cloud, guided by a semi-public contract executed on a machine that interacts with the blockchain.

Redirect link: https://bismuth.cz/casino
Link to service: http://bismuth.live:5492/
Link to application source: https://github.com/hclivess/Bismuth/blob/master/zircodice_dappie.py
Link to web interface source: https://github.com/hclivess/Bismuth/blob/master/zircodice_web.py

### BIS HD PoC
Proof of concept deterministic RSA address generation for Bismuth.

Link to source: https://github.com/jimhsu/bis-hd-poc

### Bismuth How-Tos

Various how tos and base info for Bismuth Crypto Currency . Wallet, mining, nodes and such.

- Link to source: https://github.com/EggPool/BismuthHowto

### Public Key Recovery Tool
Recovers public key from your private key, which needs to be unencrypted for this purpose.

- Link to source: https://github.com/hclivess/Bismuth/blob/master/recovery.py

### HTML Interpreter
A tool which enables you to read HTML data from the Bismuth blockchain. Can be extended to build various social or news platforms at your will.

- Link to service: http://bismuth.live:4585
- Link to source: https://github.com/hclivess/BismuthProjects/blob/master/html_dappie.py

### Vanity Address Generator
Enables you to generate a Bismuth address with specific symbols in it. Uses CPU for cycling, will take a long time to generate desirable address with more than 3 symbols.

- Link to source: https://github.com/hclivess/BismuthProjects/blob/master/vanity.py

### Transaction Anonymizer
Transaction mixing service that is completely anonymous, transactions are encrypted with the recipient private key and split to an arbitrary number of transactions before being sent back. Still under development. Running on 340c195f768be515488a6efedb958e135150b2ef3e53573a7017ac7d , you can send transactions in for mixing with the following Openfield data: anon:number_of_txs:target_address (no msg, just encrypted). Completely private contract executed in a cloud machine.

- Link to source: https://github.com/hclivess/BismuthProjects/blob/master/anon_dappie.py

### GeoMap
Integration of Bismuth node IPs with the Google Maps API, displays a global map of Bismuth nodes.

- Link to service: http://bismuth.live:5493
- Link to source: https://github.com/bismuthfoundation/geomarkers

### Bismuth Process Monitor
A monitoring service which displays status of the bundled Bismuth services.

- Link to service: http://bismuth.live
- Link to source: https://github.com/hclivess/BismuthProjects/blob/master/bisprocmon.py

### Bismuth Compilation Script

Enables creation of executables for Windows users, can be adjusted to suit individual needs. Every .py file and project present in the GitHub directory can be compiled to be used on various machines. The compiler of choice is PyInstaller.

- Link to source: https://github.com/hclivess/Bismuth/blob/master/compile_pyinstaller.cmd

### GPU Miner Source
Public GPU miner source code for Bismuth by gladimor.

- Link to source: https://github.com/hclivess/Bismuth-GPU-miner

### Bismuth Documentation
Documentation of the Bismuth project

- Link to service: https://bismuth.cz/doc
- Link to source: https://github.com/hclivess/BismuthDocumentation

### Bisdom
Bismuth 2D online city

### Bismuth Boulevard
Bismuth 3D online city

- Link to service: https://heatnodes.org/3D/bis

## Reference Projects
### Pool
The original pool implementation for Bismuth, written for the originally bundled CPU miner.

- Link to application source: https://github.com/hclivess/BismuthProjects/blob/master/poolware_dappie.py
- Link to web interface source: https://github.com/hclivess/BismuthProjects/blob/master/poolware_explorer.py

### CPU Miner
The original CPU miner to be used solely or with the pool.

- Link to application source: https://github.com/hclivess/BismuthProjects/blob/master/miner.py

### Proof of Transaction PoC
An outdated version of Bismuth which used Proof of Transactions instead of Poof of Work as a consensus algorithm. Found effectively not very viable.

- Link to source: https://github.com/hclivess/Bismuth_PoT

### HarryR’s Pool and fast CPU miner
One of the first Bismuth pools, developed by the former community member

- Link to source: https://github.com/hclivess/Bismuth_pool
