# Awesome Blockchain Rust

*Useful components for building blockchains in Rust. Includes: cryptography, distributed, p2p, consensus, etc*

- [Blockchains](#blockchains)
- [Blockchain Frameworks](#blockchain-frameworks)
- [Cross-Chain](#cross-chain)
- [Virtual Machines](#virtual-machines)
- [General-Purpose Consensus](#general-purpose-consensus)
- [P2P Network Libraries](#p2p-network-libraries)
- [Cryptography](#cryptography)
- [Layer2](#layer2)
- [Dapps](#dapps)
- [Other](#other)
- [Contribute](#contribute)
- [License](#license)

## Blockchains

- [Aleo](https://github.com/AleoHQ) - A blockchain with zero-knowledge transactions.
- [Aleph Zero](https://github.com/aleph-zero-foundation) - DAG, PoS, snark smart contracts (substrate based).
- [Anoma.network](https://github.com/anoma) - PoS blockchain with privacy.
- [Aptos Network](https://github.com/aptos-labs) - Building the safest and most scalable Layer 1 blockchain.
- [Bitcoin Cash](https://github.com/be-cash/bitcoin-cash) - A library for creating and parsing Bitcoin Cash transactions.
- [Casper](https://github.com/casper-network/casper-node) - A decentralized L1 PoS blockchain designed to accelerate enterprise and developer adoption.
- [Chainflip](https://github.com/chainflip-io/chainflip-backend/) - Native Cross-Chain Swaps.
- [CITA](https://github.com/cryptape/cita) - A high performance blockchain kernel for enterprise users.
- [CodeChain](https://github.com/CodeChain-io/codechain) - Programmable multi-asset chain.
- [Concordium](https://github.com/Concordium) - Privacy centric (zk) PoS chain, yet with built in identities and rust smart contracts.
- [Conflux](https://github.com/Conflux-Chain/conflux-rust) - The Rust implementation of Conflux protocol.
- [Darwinia](https://github.com/darwinia-network/darwinia) - Relay chain of Darwinia Network, can connect to Polkadot as parachain in Polkadot Model.
- [Dusk.network](https://github.com/dusk-network) - Privacy PoS using zk (plonk).
- [Enigma](https://github.com/enigmampc/enigma-core) secures the decentralized web.
- [MultiversX](https://github.com/multiversx) - Sharded Smart Contracts execution platform with a PoS consensus mechanism.
- [Exonum](https://github.com/exonum/exonum) - An extensible open-source framework for creating private/permissioned blockchain applications.
- [Forest](https://github.com/ChainSafe/forest) - An implementation of Filecoin written in Rust.
- [Fuel](https://github.com/FuelLabs/fuel-core) - Rust full node implementation of the Fuel protocol.
- [Gear](https://github.com/gear-tech/gear) - Computational component of Polkadot network.
- [Grin](https://github.com/mimblewimble/grin) - Minimal implementation of the MimbleWimble protocol.
- [Holochain](https://github.com/holochain/holochain) - The core Holochain framework written in rust, a container, and hdk-rust library for writing Zomes.
- [Huobi Chain](https://github.com/HuobiGroup/huobi-chain) - The next generation high performance public chain for financial infrastructure.
- [Interledger](https://github.com/interledger-rs/interledger-rs) - An easy-to-use, high-performance Interledger implementation written in Rust.
- [Internet Computer Protocol (ICP)](https://github.com/dfinity/ic) - The world’s first blockchain that runs at web speed and can increase its capacity without bound.
- [Internet of People](https://github.com/Internet-of-People/iop-rs) - Decentralized software stack that provides the building blocks and tools to support a decentralized society.
- [Libra](https://github.com/libra/libra) - Global currency and financial infrastructure that empowers billions of people.
- [Lighthouse](https://github.com/sigp/lighthouse) - Fast and secure Ethereum 2.0 client.
- [Namada](https://github.com/anoma/namada) - Proof-of-Stake L1 for interchain asset-agnostic privacy.
- [NEAR](https://github.com/nearprotocol/nearcore) - NEAR Protocol - scalable and usable blockchain.
- [Nervos CKB](https://github.com/nervosnetwork/ckb) - Nervos CKB is a public permissionless blockchain, the common knowledge layer of Nervos network.
- [NYM](https://github.com/nymtech/nym) - Selective privacy via a mixnet preventing metadata analysis.
- [Nomic](https://github.com/nomic-io/nomic) - Nomic is a high-performance Bitcoin sidechain which is part of the Cosmos network.
- [Mina Protocol](https://github.com/ChainSafe/mina-rs) - A rust implementation of the mina succinct blockchain.
- [Mir Protocol](https://github.com/mir-protocol) - A succinct blockchain powered by (plonk based) zero-knowledge proofs.
- [OpenEthereum](https://github.com/openethereum/openethereum) - The Ethereum Rust client.
- [Parity Bitcoin](https://github.com/paritytech/parity-bitcoin) - The Parity Bitcoin client.
- [Parity Ethereum](https://github.com/paritytech/parity-ethereum) - The fast, light, and robust EVM and WASM client.
- [Parity Zcash](https://github.com/paritytech/parity-zcash) - Rust implementation of Zcash protocol.
- [Polkadot](https://github.com/paritytech/polkadot) - Polkadot Node Implementation.
- [Polymesh](https://github.com/PolymathNetwork/Polymesh) - The Polymesh blockchain (built on Substrate) is an identity orientated chain for the issuance, lifecycle management and settlement of regulated securities.
- [QAN](https://github.com/QANplatform/its_alive) - Post-quantum blockchain.
- [Radix](https://github.com/radixdlt/radixdlt-scrypto) - Sharded smart contract DeFi platform.
- [RsNano](https://github.com/simpago/rsnano-node) - A rust port of Nano: the eco-friendly & feeless digital currency.
- [Setheum](https://github.com/Setheum-Labs/Setheum) - SETHEUM : “Secure Evergreen Truthful Heterogeneous Economically Unbiased Market” is an Ethical DeFi-friendly Blockchain (built on Substrate) working on achieving mass adoption, security, scalability, affordability, inclusivity and ethical DeFi Governance.
- [Shasper](https://github.com/paritytech/shasper) - Parity Shasper beacon chain implementation using the Substrate framework.
- [Solana](https://github.com/solana-labs/solana) - Blockchain Rebuilt for Scale.
- [Stacks 2.0](https://github.com/blockstack/stacks-blockchain) - Proof of Transfer blockchain from Blockstack.
- [Sui Network](https://github.com/MystenLabs/sui) - A next-generation smart contract platform with high throughput, low latency, and an asset-oriented programming model powered by the Move programming language.
- [Tari](https://github.com/tari-project) - The Tari Digital Assets Protocol.
- [Tendermint](https://github.com/informalsystems/tendermint-rs) - Tendermint is a high-performance blockchain consensus engine for Byzantine fault tolerant applications.
- [Witnet](https://github.com/witnet/witnet-rust) - Open source implementation of Witnet decentralized oracle network protocol in Rust.
- [xx-network](https://github.com/xx-labs/xxchain) - Post-quantum blockchain, mixnet privacy preventing metadata analysis.
- [Zebra](https://github.com/ZcashFoundation/zebra) - An ongoing Rust implementation of a Zcash node.
- [Zero-chain](https://github.com/LayerXcom/zero-chain) - A privacy-preserving blockchain on Substrate.

## Blockchain Frameworks

- [Substrate](https://github.com/paritytech/substrate) - The platform for blockchain innovators.
- [slingshot](https://github.com/stellar/slingshot) - A new blockchain architecture under active development, with a strong focus on scalability, privacy and safety.
- [Tendermint ABCI](https://github.com/informalsystems/tendermint-rs/tree/master/abci) - Tendermint ABCI server, written in the Rust programming language.
- [Orga](https://github.com/nomic-io/orga) - A high-performance state machine engine designed for Tendermint-based blockchain applications.
- [Anchor](https://github.com/coral-xyz/anchor) is a framework for Solana's Sealevel runtime providing several convenient developer tools for writing smart contracts.

## Cross-Chain

- [AtomicDEX](https://github.com/KomodoPlatform/atomicDEX-API) - Cross-chain and cross-protocol p2p orderbook based decentralized exchange and interoperability bridge (self-custodial).
- [Comit](https://github.com/comit-network/) - An open protocol facilitating trustless cross-blockchain applications.
- [ibc-rs](https://github.com/cosmos/ibc-rs) - Rust implementation of the Inter-Blockchain Communication (IBC) protocol.
- [Hermes](https://github.com/informalsystems/hermes) - Rust implementation of an Inter-Blockchain Communication (IBC) relayer.
- [Hyperlane](https://github.com/hyperlane-xyz/hyperlane-monorepo) - Framework for permissionless, modular interoperability with the offchain clients are written in Rust, as well as the smart contracts for Solana VM and CosmWasm.

## Virtual Machines

- [CKB-VM](https://github.com/nervosnetwork/ckb-vm) - RISC-V virtual machine.
- [CosmWasm](https://github.com/CosmWasm/cosmwasm) - Multi-chain smart contract platform built for the Cosmos ecosystem.
- [EVM Parity](https://github.com/paritytech/parity-ethereum/tree/master/evmbin) - Parity implementation of EVM.
- [FuelVM](https://github.com/FuelLabs/fuel-vm) - Interpreter for the FuelVM, a blazingly fast blockchain virtual machine.
- [FVM](https://github.com/filecoin-project/ref-fvm) - The Filecoin Virtual Machine is a hypervisor-inspired Wasm execution environment that supports multiple runtimes, including the EVM.
- [Lunatic](https://github.com/lunatic-solutions/lunatic) - Erlang-inspired runtime for WebAssembly.
- [Polygon Miden](https://github.com/maticnetwork/miden) - SNARK based VM.
- [SVM](https://github.com/spacemeshos/svm) - Spacemesh Virtual Machine.
- [Wasmi](https://github.com/paritytech/wasmi) - WebAssembly interpreter.
- [Wasmer](https://github.com/wasmerio/wasmer) - A convenient Rust wrapper over WebAssembly backends.
- [Wasmtime](https://github.com/CraneStation/wasmtime) - Standalone JIT-style runtime for WebAssembly, using Cranelift.
- [Zinc](https://github.com/matter-labs/zinc) - Zinc zk smart contract language.

## General-Purpose Consensus

- [Raft](https://github.com/pingcap/raft-rs) - Raft distributed consensus algorithm implemented in Rust.
- [Honey Badger](https://github.com/poanetwork/hbbft) - An implementation of the paper "Honey Badger of BFT Protocols".
- [Narwhal](https://github.com/MystenLabs/narwhal) - The consensus layer used by Sui.

## P2P Network Libraries

- [chamomile](https://github.com/placefortea/chamomile) - P2P libraryobust stable connection on p2p/distributed network.
- [crust](https://github.com/maidsafe/crust) - Reliable P2P network connections in Rust with NAT traversal.
- [rust-libp2p](https://github.com/libp2p/rust-libp2p) - The Rust Implementation of the libp2p networking stack.
- [Tentacle](https://github.com/driftluo/tentacle) - A multiplexed p2p network framework that supports custom protocols.
- [P2P NAT-Traversal](https://github.com/ustulation/p2p) - NAT Traversal techniques for p2p communication.
- [qp2p](https://github.com/maidsafe/qp2p) - Peer-to-peer communications library for Rust based on QUIC protocol.
- [sn_routing](https://github.com/maidsafe/sn_routing) - Specialised storage DHT ffor routing.

## Cryptography

- [Awesome Cryptography Rust](https://github.com/rust-cc/awesome-cryptography-rust) - Awesome list.
- [Dalek Cryptography](https://github.com/dalek-cryptography) - Libraries for cryptographic primatives.
- [Za!](https://github.com/adria0/za) - An experimental rust zksnarks compiler with embeeded bellman-bn128
  prover.
- [OpenZKP](https://github.com/0xProject/OpenZKP) - Pure Rust implementations of Zero-Knowledge Proof systems.
- [Microsoft Nova](https://github.com/microsoft/Nova) - Rust recursive snark without trusted setup.
- [Arkworks](https://github.com/arkworks-rs) - An ecosystem for developing and programming with zkSNARKs

## Layer2

- [Arbitrum's arb-os](https://github.com/OffchainLabs/arb-os) - ArbOS is the "operating system" that runs an eth Layer 2 on an Arbitrum chain,
- [Noir language](https://github.com/noir-lang/noir) - Noir is a Domain Specific Language for SNARK proving systems.
- [Penumbra](https://github.com/penumbra-zone/penumbra) - PoS network providing privacy to the Cosmos ecosystem.
- [Rust-Lightning](https://github.com/rust-bitcoin/rust-lightning) - Bitcoin Lightning library.
- [zkSync](https://github.com/matter-labs/zksync) - Matter Labs' scaling eth L2 engine secured by zero-knowledge proofs.

## Dapps

- [Serum-dex](https://github.com/project-serum/serum-dex) - A decentralized exchange built on Solana.
- [SewUp](https://github.com/second-state/SewUp) - A library to help you build your Ethereum webassembly contract with Rust and just like develop in a common backend.
- [Sienna Network](https://github.com/SiennaNetwork/SiennaNetwork) - A privacy-first and cross-chain decentralized finance platform where you can privately swap, lend and convert your tokens into their private equivalent.
- [ink!athon](https://github.com/scio-labs/inkathon) - Full-Stack DApp Boilerplate for Substrate and ink! Smart Contracts.

## Other

- [abscissa](https://github.com/iqlusioninc/abscissa) - Micro-framework for CLI tools with strong focus on security.
- [tesseracts](https://github.com/adria0/tesseracts) - A small block explorer for geth PoAs written in rust.
- [merk](https://github.com/nomic-io/merk) - High performance Merkle key/value store written in Rust, based on RocksDB.
- [ERC-4337 Bundler](https://github.com/Vid201/aa-bundler/) - An ongoing Rust implementation of an ERC-4337 (Account Abstraction) Bundler.

## Contribute

Contributions are most welcome.

GitHub: [Awesome Blockchain Rust](https://github.com/rust-in-blockchain/awesome-blockchain-rust)


## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
