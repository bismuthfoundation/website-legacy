# Summary

The first Python blockchain.

Based around modularity and efficiency with ready-made decentralized applications.

Optional turing complete public and private contracts.

Welcome to Bismuth, a digital distributed self-regulating database system whose primary application is currency, and its first application is mining. It comes with a set of DAPPs out-of-the-box. Bismuth is not based on code of BTC or any of it’s derivates, it is only inspired by some ideas laid down by Satoshi Nakamoto (BitCoin), Sunny King (Peercoin), NXT and ETH developers.

Bismuth does not draw any code from other repositories, instead it reformulates the cryptocurrency code in its own terms to be easily readable, compatible across all platforms, integrated into business solutions with utmost ease and most importantly open for development to wide public through it’s simplicity, while minimizing the security risk for custom code implementations.

Bismuth is a decentralized transaction platform focused on modularity and open source approach. It comes with default decentralized applications and tools out of the box, not only to be used by everyone, but also to be hosted by anyone. These applications are supplied as interpretation engines, which prevents blockchain bloat. Inspired by Satoshi’s whitepaper, Bismuth also offers optional hyperblocks as a pruning mechanism, a system which greatly reduces disk space usage and increases execution speed.

On-chain messaging and data storage is available in both public and encrypted forms. Together with Tor support and transaction mixing decentralized application, Bismuth offers top-of-the-line privacy features.

- System: Proof of work (custom implementation)
- Hashing algorithm: SHA224
- Signing algorithm: PKCS1_v1_5
- Transaction size: ~650 bytes + data fees
- Mining reward: Tapering from 15 at block 1 to 0 at block 10,000,000
- Difficulty: Previous difficulty + log2 of block per day divided by blocks per day (min of daily median)
- Difficulty retarget: Every block
- Maximum supply: 99,999,980 (109,999,978 including dev rewards)
- Smallest unit: 0.00000001
- Confirmations before respending: 0
- Plaintext peer list file
- Tor proxy support
- Optimized towards efficiency
- Dual database system for maximum performance
- Database compression/pruning
- Arbitrary data storage ecosystem and philosophy
- Address-based anonymizing transaction mixer
- Assymetric message and data encryption
- Batteries included: Pool, casino, mixer, peer map
- Node options fully configurable
- All layers built from scratch
- 100% OpenSource
- Port: 5658
- More information about exchanges and services can be found in the announcement thread on the Bitcointalk forum: https://bitcointalk.org/index.php?topic=1896497.msg18827587#msg18827587
