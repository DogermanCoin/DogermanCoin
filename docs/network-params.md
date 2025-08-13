# DogermanCoin – Network Parameters

**Document Version:** 1.0  
**Date:** 2025-08-13  
**Maintainer:** DogermanCoin Core Developers  

---

## Mainnet

| Parameter | Value |
|-----------|-------|
| **PUBKEY_ADDRESS** | `0x1F` (`D...`) |
| **SCRIPT_ADDRESS** | `0x32` (`M...`) |
| **WIF** | `0x9F` |
| **P2P Port** | `10333` |
| **RPC Port** | `10332` |
| **ChainID** | `1121` |
| **Genesis Address** | `DsWxMHFnom7znXnGCKohAbcJvRYzExmPYM` |
| **Private Key (WIF)** | `6MGbYYZ6bJEDdREz2ZosBpTA5gBrXVYkn9JEcrX6z8gDctopnp6` |
| **Public Key (Compressed)** | `025cb39c1782afaf2ed0e0b7eebe03a4b3880d66f27d96ac8f32fd893d65229b36` |
| **Time** | `1755107037` (UTC: 2025-08-13 17:43:57) |
| **Bits (Difficulty)** | `0x207fffff` *(test value; recommended: `0x1e0ffff0`)* |
| **Nonce** | `0` |
| **Genesis Block Hash** | `1ecc07721e5fa2c4a588a731b53da7f5ff6b215dd7fcabb3caff2297bd6e5d17` |
| **Merkle Root** | `44a86fc18ebc1d536faee6011a47d2082cd1bbf28bd57a157ff0ca1140bced08` |

---

## LocalNet (Private Real Network)

| Parameter | Value |
|-----------|-------|
| **PUBKEY_ADDRESS** | `0x2A` (`E...`) |
| **SCRIPT_ADDRESS** | `0x35` (`N...`) |
| **WIF** | `0xAA` |
| **P2P Port** | `11333` |
| **RPC Port** | `11332` |
| **ChainID** | `1122` |
| **Genesis Address** | `J9E8NNSjCchs3YzAG6C6NhJLZMujRdbbxa` |
| **Private Key (WIF)** | `6iqwnseb1z1NH7en42UAnMJR6uC17Br4e6DLTcQwUmGbczxSzuF` |
| **Public Key (Compressed)** | `024633a00280fa69fbfe1e9a3ce5b698cc6b3719bc277891a38f64905b78902b20` |
| **Time** | `1755105711` (UTC: 2025-08-13 17:21:51) |
| **Bits (Difficulty)** | `0x1e0ffff0` |
| **Nonce** | `1286959` |
| **Genesis Block Hash** | `2d9e3f6ce5f2c12afeed2232d96e388c2857557ff4b31ab107c3d55dce0e0000` |
| **Merkle Root** | `3bd13e80ef900c0f18507f82ddd50502cc751971a85ea23c3e52db34159d97c1` |

---

## Notes
1. All parameters are **unique** to DogermanCoin and must not be reused by other projects.  
2. Genesis block hash and address act as provenance proof for each network.  
3. This document's timestamp and commit hash act as a permanent public record.  
4. Both **Mainnet** and **LocalNet** are real networks with distinct ChainIDs to prevent collisions.  
5. **Security Note:** Private keys for genesis blocks must be secured offline and never reused for wallets.

