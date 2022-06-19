# Awesome Blockchain Rust

*Useful components for building blockchains in Rust. include: cryptography, distributed, p2p, consensus, etc*

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
- [Aleo](https://developer.aleo.org/aleo/getting_started/overview).
  Leo is a rust flavoured zk language.
- [Aleph Zero](https://alephzero.org/).
  DAG, PoS, snark smart contracts (substrate based).
- [Anoma.network](https://anoma.network/).
  PoS blockchain with privacy.
- [Bitcoin Cash](https://github.com/be-cash/bitcoin-cash).
  A library for creating and parsing Bitcoin Cash trasactions.
- [CITA](https://github.com/cryptape/cita).
  A high performance blockchain kernel for enterprise users.
- [CodeChain](https://github.com/CodeChain-io/codechain).
  Programmable multi-asset chain.
- [Concordium](https://concordium.com/).
  Privacy centric (zk) PoS chain, yet with built in identities and rust smart contracts.
- [Conflux](https://github.com/Conflux-Chain/conflux-rust).
  The Rust implementation of Conflux protocol.
- [Darwinia](https://github.com/darwinia-network/darwinia).
  Relay chain of Darwinia Network, can connect to Polkadot as
  parachain in Polkadot Model.
- [Dusk.network](https://dusk.network/).
  Privacy PoS using zk (plonk).
- [Enigma](https://github.com/enigmampc/enigma-core) secures the
  decentralized web.
- [Elrond](https://elrond.com/).
  Elrond (EGOLD( - scalable and usable blockchain, written is Rust and
  has smart contracts in Rust.
- [Exonum](https://github.com/exonum/exonum).
  An extensible open-source framework for creating
  private/permissioned blockchain applications.
- [Forest](https://github.com/ChainSafe/forest).
  An implementation of Filecoin written in Rust.
- [Fuel](https://github.com/FuelLabs/fuel-core).
  Rust full node implementation of the Fuel v2 protocol.
- [Gear](https://github.com/gear-tech/gear).
  Computational component of Polkadot network.
- [Grin](https://github.com/mimblewimble/grin).
  Minimal implementation of the MimbleWimble protocol.
- [Holochain](https://github.com/holochain/holochain).
  The core Holochain framework written in rust, a container, and
  hdk-rust library for writing Zomes.
- [Huobi Chain](https://github.com/HuobiGroup/huobi-chain).
  The next generation high performance public chain for financial
  infrastructure.
- [Interledger](https://github.com/interledger-rs/interledger-rs).
  An easy-to-use, high-performance Interledger implementation written
  in Rust.
- [Internet of People](https://github.com/Internet-of-People/iop-rs).
  Decentralized software stack that provides the building blocks and
  tools to support a decentralized society.
- [Libra](https://github.com/libra/libra).
  Global currency and financial infrastructure that empowers billions
  of people.
- [Lighthouse](https://github.com/sigp/lighthouse).
  Fast and secure Ethereum 2.0 client.
- [NEAR](https://github.com/nearprotocol/nearcore).
  NEAR Protocol - scalable and usable blockchain.
- [Nervos CKB](https://github.com/nervosnetwork/ckb).
  Nervos CKB is a public permissionless blockchain, the common
  knowledge layer of Nervos network.
- [NYM](https://github.com/nymtech/nym).
  Selective privacy via a mixnet preventing metadata analysis.
- [Nomic](https://github.com/nomic-io/nomic).
  Nomic is a high-performance Bitcoin sidechain which is part of the
  Cosmos network.
- [Mina Protocol](https://github.com/ChainSafe/mina-rs).
  A rust implementation of the mina succinct blockchain.
- [Mir Protocol](https://mirprotocol.org/).
  A succinct blockchain powered by zero-knowledge proofs. (plonk based)
- [OpenEthereum](https://github.com/openethereum/openethereum).
  The Ethereum Rust client
- [Parity Bitcoin](https://github.com/paritytech/parity-bitcoin).
  The Parity Bitcoin client.
- [Parity Ethereum](https://github.com/paritytech/parity-ethereum).
  The fast, light, and robust EVM and WASM client.
- [Parity Zcash](https://github.com/paritytech/parity-zcash).
  Rust implementation of Zcash protocol.
- [Polkadot](https://github.com/paritytech/polkadot).
  Polkadot Node Implementation.
- [Polymesh](https://github.com/PolymathNetwork/Polymesh).
  The Polymesh blockchain (built on Substrate) is an identity orientated chain
  for the issuance, lifecycle management and settlement of regulated securities.
- [QAN](https://github.com/QANplatform/its_alive).
  Post-quantum blockchain.
- [Radix](https://github.com/radixdlt/radixdlt-scrypto).
  Sharded smart contract DeFi platform.
- [Setheum](https://github.com/Setheum-Labs/Setheum).
  SETHEUM : “Secure Evergreen Truthful Heterogeneous Economically Unbiased Market”
  is an Ethical DeFi-friendly Blockchain (built on Substrate) working on achieving
  mass adoption, security, scalability, affordability, inclusivity and ethical DeFi Governance.
- [Shasper](https://github.com/paritytech/shasper).
  Parity Shasper beacon chain implementation using the Substrate
  framework.
- [Solana](https://github.com/solana-labs/solana).
  Blockchain Rebuilt for Scale.
- [Stacks 2.0](https://github.com/blockstack/stacks-blockchain).
  Proof of Transfer blockchain from Blockstack.
- [Tari](https://github.com/tari-project).
  The Tari Digital Assets Protocol.
- [Tendermint](https://github.com/informalsystems/tendermint-rs).
  Tendermint is a high-performance blockchain consensus engine for
  Byzantine fault tolerant applications.
- [Witnet](https://github.com/witnet/witnet-rust).
  Open source implementation of Witnet decentralized oracle network
  protocol in Rust.
- [xx-network](https://github.com/xx-labs/xxchain).
  Post-quantum blockchain, mixnet privacy preventing metadata analysis. (Substrate rust+go)
- [Zebra](https://github.com/ZcashFoundation/zebra).
  An ongoing Rust implementation of a Zcash node.
- [Zero-chain](https://github.com/LayerXcom/zero-chain).
  A privacy-preserving blockchain on Substrate.

## Blockchain Frameworks
- [Substrate](https://github.com/paritytech/substrate).
  The platform for blockchain innovators.
- [slingshot](https://github.com/stellar/slingshot).
  A new blockchain architecture under active development, with a
  strong focus on scalability, privacy and safety.
- [Tendermint ABCI](https://github.com/tendermint/rust-abci).
  Tendermint ABCI server, written in the Rust programming language.
- [Orga](https://github.com/nomic-io/orga).
  A high-performance state machine engine designed for
  Tendermint-based blockchain applications.

## Cross-Chain
- [Comit](https://comit.network/) is an open protocol facilitating
  trustless cross-blockchain applications.
- [IBC](https://github.com/informalsystems/ibc-rs).
  Rust implementation of Cosmos' Interblockchain Communication Protocol
  (IBC).

## Virtual Machines
- [CKB-VM](https://github.com/nervosnetwork/ckb-vm).
  RISC-V virtual machine.
- [CosmWasm](https://www.cosmwasm.com).
  Multi-chain smart contract platform built for the Cosmos ecosystem.
- [EVM Parity](https://github.com/paritytech/parity-ethereum/tree/master/evmbin).
  Parity implementation of EVM.
- [FuelVM](https://github.com/FuelLabs/fuel-vm)
  FuelVM interpreter in Rust.
- [Lunatic](https://github.com/lunatic-solutions/lunatic).
  Erlang-inspired runtime for WebAssembly.
- [Polygon Miden](https://github.com/maticnetwork/miden).
  SNARK based VM.
- [SVM](https://github.com/spacemeshos/svm)
  Spacemesh Virtual Machine.
- [Wasmi](https://github.com/paritytech/wasmi).
  WebAssembly interpreter.
- [Wasmer](https://wasmer.io/).
  A convenient Rust wrapper over WebAssembly backends.
- [Wasmtime](https://github.com/CraneStation/wasmtime).
  Standalone JIT-style runtime for WebAssembly, using Cranelift.
- [Zinc](https://github.com/matter-labs/zinc).
  Zinc zk smart contract language.

## General-Purpose Consensus
- [Raft](https://github.com/pingcap/raft-rs).
  Raft distributed consensus algorithm implemented in Rust.
- [Honey Badger](https://github.com/poanetwork/hbbft).
  An implementation of the paper "Honey Badger of BFT Protocols" in
  Rust.
- [Narwhal](https://github.com/MystenLabs/narwhal).
  The consensus layer used by Sui.

## P2P Network Libraries
- [chamomile](https://github.com/placefortea/chamomile).
  P2P library. Support build robust stable connection on
  p2p/distributed network.
- [crust](https://github.com/maidsafe/crust).
  Reliable P2P network connections in Rust with NAT traversal. One of
  the most needed libraries for any server-less / decentralised
  projects.
- [rust-libp2p](https://github.com/libp2p/rust-libp2p).
  The Rust Implementation of the libp2p networking stack.
- [Tentacle](https://github.com/driftluo/tentacle).
  A multiplexed p2p network framework that supports custom protocols
- [P2P NAT-Traversal](https://github.com/ustulation/p2p).
  NAT Traversal techniques for p2p communication.
- [qp2p](https://github.com/maidsafe/qp2p).
  Peer-to-peer communications library for Rust based on QUIC protocol.
- [sn_routing](https://github.com/maidsafe/sn_routing).
  Routing - specialised storage DHT.

## Cryptography
- [Awesome Cryptography Rust](https://github.com/rust-cc/awesome-cryptography-rust).
- [Dalek Cryptography](https://github.com/dalek-cryptography).
- [Za!](https://github.com/adria0/za).
  An experimental rust zksnarks compiler with embeeded bellman-bn128
  prover.
- [OpenZKP](https://github.com/0xProject/OpenZKP).
  Pure Rust implementations of Zero-Knowledge Proof systems.
- [Microsoft Nova](https://github.com/microsoft/Nova).
  Rust recursive snark without trusted setup.
- [Arkworks](https://github.com/arkworks-rs).
  An ecosystem for developing and programming with zkSNARKs

## Layer2
- [Arbitrum's arb-os](https://github.com/OffchainLabs/arb-os)
  ArbOS is the "operating system" that runs an eth Layer 2 on an Arbitrum chain,
- [Noir language](https://github.com/noir-lang/noir).
  Noir is a Domain Specific Language for SNARK proving systems. (Aztec eth L2)
- [Penumbra](https://penumbra.zone/).
  PoS network providing privacy to the Cosmos ecosystem.
- [Rust-Lightning](https://github.com/rust-bitcoin/rust-lightning)
  is a Bitcoin Lightning library written in Rust.
  The main crate, lightning, does not handle networking,
  persistence, or any other I/O. Thus, it is runtime-agnostic,
  but users must implement basic networking logic,
  chain interactions, and disk storage.
- [zkSync](https://github.com/matter-labs/zksync).
  Matter Labs' scaling eth L2 engine secured by zero-knowledge proofs.

## Dapps
- [Serum-dex](https://github.com/project-serum/serum-dex).
  A decentralized exchange built on Solana.
- [SewUp](https://github.com/second-state/SewUp).
  A library to help you build your Ethereum webassembly contract with
  Rust and just like develop in a common backend.
- [Sienna Network](https://github.com/SiennaNetwork/SiennaNetwork).
  A privacy-first and cross-chain decentralized finance platform where
  you can privately swap, lend and convert your tokens into their
  private equivalent.

## Other
- [abscissa](https://github.com/iqlusioninc/abscissa).
  Micro-framework for CLI tools with strong focus on security.
- [tesseracts](https://github.com/adria0/tesseracts).
  A small block explorer for geth PoAs written in rust.
- [merk](https://github.com/nomic-io/merk).
  High performance Merkle key/value store written in Rust, based on
  RocksDB.


## Contribute
Contributions are most welcome.

GitHub: [Awesome Blockchain
Rust](https://github.com/rust-in-blockchain/awesome-blockchain-rust)


## License
[![Creative Commons
License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0
International License](http://creativecommons.org/licenses/by/4.0/).
