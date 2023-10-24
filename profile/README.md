# ink! Dev Hub <br/>

## Welcome to the ink! Dev Hub, where we share our work and our passion for ink! smart contracts and dApps development.

![ink!devhub](https://github.com/inkdevhub/brand-assets/blob/main/PNG/ink!devhub%20github%20banner.png)

## About ink! Dev Hub
ink! Dev Hub integrates Swanky Suite tool, DRink! Tool, as well as ink! examples with an aim to improve developer tooling around WASM (ink!) smart contracts. 

We aim to contribute to the development of a more robust, secure, and accessible ink! smart contract environment for developers, helping users accomplish their tasks promptly and effortlessly while utilizing advanced features when required.

ink! Dev Hub encourages more web3 developers to explore and adopt WASM (ink!) smart contracts within the Polkadot and Kusama ecosystems, creating a thriving developer community that can bring Polkadot's potential to life. By focusing on WASM-based ink! smart contracts, ink! Dev Hub is essentially future-proofing the Polkadot and Kusama ecosystems, ensuring they remain at the forefront of blockchain technology.

## Swanky
**Swanky** is designed to be the go-to developer tool for every aspect of developing WASM (ink!) smart contracts for Polkadot, from scaffolding to live-net deployment. While some tools currently exist, Swanky's intent is to integrate and extend these tools as necessary, offering a more streamlined, dev-friendly experience.

The development of a smart contract project follows a clear, necessary sequence: scaffolding a new project, building and testing locally, deploying and testing on a test network, and finally deploying on a live network. Swanky is designed to provide support at every stage of this process, making it an indispensable asset for any WASM (ink!) smart contract developer.

## DRink!
**DRink!** library provides a minimal viable functionality for arbitrary runtime interaction and standard contract-related operations (like code upload, instantiation or calling). DRink! was designed with a particular trade-off in mind: giving up the whole node layer with simultaneously gaining direct access to the runtime. For that, we make use of the existing machinery exposed by the Substrate framework, that before was primarily used for pallet unit testing. We build (in-memory) minimal runtime supporting ink! smart contracts (although the library supports arbitrary ink!-compatible runtime) and expose a convenient, synchronous interface for interacting with the chain.

Since there is no node running in the background, we can benefit from omitting node/network configuration issues, blocktime/finalization delays or overhead coming from asynchronous communication between e2e client and RPC chain service.

DRink! originally came with `drink-cli`: a command-line tool with terminal graphic interface for local playing with contracts.


## Teams' background 

**[Astar Network](https://astar.network/)** won its Parachain auction in January 2022, and since then has been the leading smart contract hub. Astar Foundation's core development team is the main contributor to Astar Network contributing to the Polkadot ecosystem since 2019. Astar Network is the future of smart contracts platform for multichain. The network supports the building of dApps with EVM and WASM smart contracts and offers developers true interoperability, with cross-consensus messaging (XCM) and cross-virtual machine (XVM). We are made by developers and for developers.

[**Aleph Zero**](http://alephzero.org/) is an enterprise-ready, high-performance layer 1 blockchain platform with a novel, peer-reviewed AlephBFT consensus protocol. Besides providing near-instant transaction finality, the platform offers privacy-preserving features on a public blockchain through the combination of Zero-Knowledge proofs and Multi Party Computations (MPC).

[**Phala Network**](https://www.phala.network/), a privacy-preserving cloud computing service built on Substrate, is set to operate as a parachain within the Polkadot ecosystem, providing computing power on par with existing cloud services while safeguarding the privacy of managed programs. With its off chain programming model Phat Contract running on Phala Network, it enables developers to make smart contracts even smarter.


## Swanky repositories

| repo  | type  | frontend  | tutorial  |   |
|---|---|---|---|---|
| [swanky-cli](https://github.com/swankyhub/swanky-cli)  | tool  | -  | [README](https://github.com/swankyhub/swanky-cli/blob/master/README.md)  |   |
| [swanky-node](https://github.com/swankyhub/swanky-node)  | tool  | -  | [README](https://github.com/swankyhub/swanky-node/blob/main/README.md)  |   |
| [dex](https://github.com/swankyhub/dex)   | example  | -  | [tutorial](https://docs.astar.network/docs/build/wasm/from-zero-to-ink-hero/dex/)  |   |
| [nft](https://github.com/swankyhub/nft)   | example  | -  | [tutorial](https://docs.astar.network/docs/build/wasm/from-zero-to-ink-hero/nft/)  |   |
| [manic-minter ](https://github.com/swankyhub/manic-minter)  | example  | -  | [tutorial](https://docs.astar.network/docs/build/wasm/from-zero-to-ink-hero/manic-minter/)  |   |
| [rmrk-lazy-mint](https://github.com/swankyhub/rmrk-lazy-mint)   | example  | -  | -  |   |
| [meta-transaction](https://github.com/swankyhub/meta-transaction)   | example  | -  | -  |   |
| [marketplace](https://github.com/swankyhub/marketplace)   | example  | -  | -  |   |
| [lottery](https://github.com/swankyhub/wasm-lottery)  | example  | ✅  | -  |   |
| [farming](https://github.com/swankyhub/farming)  | example  | -  | -  |   |


## DRink! repositories

| repo  | type  | frontend  | tutorial  |   |
|---|---|---|---|---|
|  |   |   |   |   |
|  |   |   |   |   |
|  |   |   |   |   |
|  |   |   |   |   |

