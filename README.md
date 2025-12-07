# 🌳 goldenera-merkletrie

**goldenera-merkletrie** is a **Java library** for implementing the **Merkle Patricia Trie (MPT)** data structure, which is essential for efficient and secure state management in blockchain applications.

---

## 💡 About Merkle Patricia Trie

MPT combines a **Merkle Tree** (for verifying data integrity via a root hash) and a **Patricia Trie** (for efficiently storing and accessing key-value pairs).

This structure forms the backbone for managing the global state (**World State**) in Ethereum-inspired systems, where **accounts**, **nonces**, and **balances** are stored.

---

## Credits & Attribution

This project contains code derived from:
- [Hyperledger Besu](https://github.com/hyperledger/besu) - Apache 2.0 License
- [Apache Tuweni](https://github.com/consensys/tuweni) - Apache 2.0 License

We are grateful to ConsenSys AG and the Hyperledger Besu team for their excellent work on MPT implementations.

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

**Important:** This project includes code from Apache 2.0 licensed projects. The original Apache 2.0 copyright notices and attributions are preserved in accordance with the Apache 2.0 license requirements. See the [NOTICE](NOTICE) file for detailed attribution information.

### Summary
- **Project License:** MIT
- **Derived Code:** Retains Apache 2.0 license where applicable
- **Modified Files:** Dual-licensed under Apache 2.0 and MIT (see NOTICE file)
