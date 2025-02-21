# Awesome Motoko [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> An awesome list of Motoko code and resources curated by the community.

> The [Motoko programming language](https://smartcontracts.org/docs/language-guide/motoko.html) is a new, modern and type safe language for developers who want to build the next generation of distributed applications to run on the [Internet Computer](https://dfinity.org) blockchain network.

## Contents

- [Applications](#applications)
  - [Canister tools](#canister-tools)
  - [Cryptocurrencies](#cryptocurrencies)
  - [Decentralized Finance](#decentralized-finance)
  - [Games](#games)
  - [Mining Platform](#mining-platform)
  - [Realestate](#realestate)
  - [Social](#social)
  - [Storage](#storage)
  - [Utilities](#utilities)
  - [Video](#video)
- [Development tools](#development-tools)
  - [Build system](#build-system)
  - [IDEs](#ides)
  - [Testing](#testing)
- [Libraries](#libraries)
  - [Algorithms](#algorithms)
  - [Cryptography](#cryptography)
  - [Data structures](#data-structures)
  - [Encoding](#encoding)
  - [Graphics](#graphics)
  - [Logging](#logging)
  - [Misc](#misc)
  - [Payment](#payment)
  - [Storage](#storage-1)
  - [Templates](#templates)
  - [Text processing](#text-processing)
  - [Web Programming](#web-programming)
- [Registries](#registries)
- [Resources](#resources)
- [Contribute](#contribute)
- [License](#license)

## Applications

Fully functional smart contract.

### Canister tools

- [candid-spaces](https://github.com/matthewhammer/candid-spaces) - A general-purpose candid data lake for canisters' data on the IC.
- [Canister Tip Jar](https://github.com/ninegua/tipjar) - Donate cycles to your favorite canisters on the Internet Computer and keep them live and healthy.
- [iCAN](https://github.com/PrimLabs/iCAN) - A Canister Management Platform, which helps you create canisters in random subnet and manage canisters status efficiently and conveniently.
- [ic-blackhole](https://github.com/ninegua/ic-blackhole) - Once a canister sets its only controller to a black hole, it becomes immutable.
- [motoko_top_up_canister](https://github.com/ORIGYN-SA/motoko_top_up_canister) - Implementation of a canister called periodically by a Node.js service; that top-up automatically user-defined canisters with cycles.

### Cryptocurrencies

- [Appic](https://github.com/Appic-Solutions/Auto_Investment) - A canister for automatically buying and selling tokens at specific times or intervals.
- [extendable-token](https://github.com/Toniq-Labs/extendable-token) - This token standard provides a ERC1155/multi-token-like approach with extensions that can add additional functionality based on the purpose of the token.
- [extendable token standard](https://github.com/aviate-labs/ext.std) - Extendable Token Standard.
- [icrc1-token-canister](https://github.com/sonicdex/icrc-1-public/) - Implementation of ICRC1 token canister
- [icrc30-mo](https://github.com/PanIndustrial-Org/icrc30.mo) - A Class+ ICRC-30 Library for providing Approve/TransferFrom to ICRC-7 NFT Canisters.
- [icrc3-mo](https://github.com/PanIndustrial-Org/icrc3.mo) - A Class+ ICRC-3 Library for adding transaction logs and archives to your canister.
- [icrc7_motoko](https://github.com/noku-team/icrc7_motoko) - An ICRC-7 standard implementation in Motoko.
- [icrc7-mo](https://github.com/PanIndustrial-Org/icrc7.mo) - A Class+ ICRC-7 Library for building NFT Canisters.
- [icrc-nft-mo](https://github.com/PanIndustrial-Org/icrc_nft.mo) - A Sample NFT combining icrc7-mo, icrc30-mo, icrc3-mo.
- [ic-nft](https://github.com/rocklabs-io/ic-nft) - A NFT standard implementation for the Internet Computer, the interfaces mainly follow the ERC721 standard.
- [ic-token](https://github.com/rocklabs-io/ic-token) - An ERC-20 style token standard implements for Motoko.
- [motoko-token](https://github.com/enzoh/motoko-token) - This package implements a simple ERC-20 style token.
- [non-fungible-token](https://github.com/DepartureLabsIC/non-fungible-token) - The goal for this project is to develop a non-fungible token standard which leverages the unique properties of the IC and enables builders to create entire experiences from a single contract.
- [token faucet](https://github.com/rocklabs-io/token-faucet) - A token faucet for [ic-token](https://github.com/rocklabs-io/ic-toke).

### Decentralized Finance

- [BrownFi](https://github.com/BrownFi/BrownFi-AMM-ICP) - Simple AMM Dex with high Capital Effifiency

### Games

- [reversi](https://github.com/ninegua/reversi) - Multiplayer Reversi Game on Internet Computer.
- [revo](https://github.com/DepartureLabsIC/revo) - A drawing game on Internet Computer.
- [superheroes](https://github.com/enzoh/superheroes) - A simple example that demonstrates how to build a CRUD application on the Internet Computer using Motoko and React.

### Mining Platform

- [loka](https://github.com/lokaverse/loka_canister) - Trustless Non-Custodial Bitcoin Mining Platform built on IC

### Realestate
- [ber](https://github.com/orgs/assets-tokenization/repositories) - Blockchain estate register with IC 

### Social

- [Formyfi](https://github.com/Talentum-id/formify) - Decentralized & fully on-chain Q&A Forms.
- [LinkedUp](https://github.com/dfinity/linkedup) - An open professional network on Internet Computer.

### Storage

- [motoko-bucket](https://github.com/PrimLabs/Bucket) - A K-V Database lib that uses stable memory to store data.
- [motoko-cdn](https://github.com/gabrielnic/motoko-cdn) - A simple storage auto-scaling solution across multiple canisters. Ie: mini-bigmap.
- [motoko-dht](https://github.com/enzoh/motoko-dht) - This canister implements a distributed hash table.
- [motoko-document-db](https://github.com/DepartureLabsIC/motoko-document-db)
- [motoko-ICSP](https://github.com/PrimLabs/ICSP) - Internet Computer Storage Protocol. This lib supports many features, such as auto-scale storage, HTTP Redirect, cycle monitor and top up self automatically. 

### Utilities

- [cleansheets](https://github.com/matthewhammer/cleansheets) - A spreadsheet-like application for the Internet Computer, written in Motoko.
- [IC Payroll](https://github.com/cosmasken/ic-payroll) - Human Resource and Payroll App hosted fully on-chain on the internet Computer. Users can hold and send ckbtc and other icrc2 compliant tokens .Allows user to send a single payment or bulk payment. Vue/Tailwindcss Frontend with Motoko Backend.
- [motoko-certified-http](https://github.com/nomeata/motoko-certified-http) - A motoko canister that does HTTP asset certification.
- [relay](https://github.com/DepartureLabsIC/relay) - Managed events infrastructure by Departure Labs.
- [SecureGuard Escrow](https://github.com/bix-tech/secure-guard-escrow) - Revolutionizing secure transactions with a blockchain-based escrow platform , ensuring safe exchanges of high-value goods and services with immutable smart contracts.

### Video

- [cancan](https://github.com/dfinity/cancan) - A scalable video-sharing service.

## Development tools

### Build system

- [dfx](https://github.com/dfinity/sdk/tree/master/src/dfx) - The DFINITY command-line execution environment (dfx) is the primary tool for creating, deploying, and managing the dapps you develop for the Internet Computer blockchain.
- [Vessel package manager](https://github.com/dfinity/vessel) - Add and manage packages, libraries, and dependencies for your Motoko programs.

### IDEs

- [Blocks](https://blocks-editor.github.io/blocks/) - An open source visual Motoko smart contract editor.
- [IntelliJ IDEA Motoko support](https://github.com/ununhexium/idea-motoko-plugin) - Adds support for the Motoko language from Dfinity.
- [motoko-playground](https://github.com/dfinity/motoko-playground) - A playground for the Internet Computer's native Motoko language.
- [Visual Studio Code](https://code.visualstudio.com/)
  - [Motoko](https://marketplace.visualstudio.com/items?itemName=dfinity-foundation.vscode-motoko) - Motoko language support maintained by official.

### Testing

- [ic-mini-terminal](https://github.com/matthewhammer/ic-mini-terminal) - Minimal keyboard input (⌨) and graphical output (📺) for programs on the Internet Computer.
- [motoko-bigtest](https://github.com/matthewhammer/motoko-bigtest) - Long-running tests as/for IC services, via a Motoko-based DSL.
- [motoko-color](https://github.com/ByronBecker/motoko-color) - A Motoko library for rendering color schemes and graphics to the terminal, based on the ANSI ASCII standard.
- [motoko-matchers](https://github.com/kritzcreek/motoko-matchers) - Composable assertions for unit testing.
  - [ic101](https://github.com/kritzcreek/ic101) - This repository demonstrates how to use the matchers library to unit test canisters on the Internet Computer.

## Libraries

### Algorithms

- [chronosphere](https://github.com/enzoh/chronosphere) - A time library for the Motoko programming language.
- [motoko-adapton](https://github.com/matthewhammer/motoko-adapton) - Dynamic dependence graph and memoization techniques in Motoko.
- [motoko-qr](https://github.com/enzoh/motoko-qr) - A QR-code generator for the Motoko programming language.
- [motoko-scc](https://github.com/nomeata/motoko-scc) - A Strongly Connected Component library for Motoko.
- [motoko-splay](https://github.com/chenyan2002/motoko-splay) - The splaying algorithm for Motoko.
- [mo-parsec](https://github.com/crusso/mo-parsec) - A [Parsec](https://hackage.haskell.org/package/parsec)-based parser combinator library for Motoko.
- [Parser Combinators](https://github.com/aviate-labs/parser-combinators.mo) - Based on Monadic Parser Combinators by Graham Hutton and Erik Meijer.
- [Sorted](https://github.com/aviate-labs/sorted.mo) - Data structures in which each element is sorted in numerical, alphabetical, or some other order.

### Cryptography

- [ecdsa-motoko](https://github.com/herumi/ecdsa-motoko) - ECDSA for Motoko.
- [ecdsa_poc](https://github.com/flyq/ecdsa_poc) - Prototype implementation of ECDSA, only for learning.
- [evm-txs](https://github.com/av1ctor/evm-txs.mo) - EVM transactions creation, encoding, and decoding library in pure Motoko.
- [libsecp256k1.mo](https://github.com/av1ctor/libsecp256k1.mo) - Motoko port of libsecp256k1.
- [motoko-bitcoin](https://github.com/tgalal/motoko-bitcoin) - Bitcoin-related libraries (Base58, RIPMED160, HMAC).
- [motoko-crc](https://github.com/enzoh/motoko-crc) - This package implements cyclic redundancy checks for the Motoko programming language.
- [motoko-CRC32](https://github.com/aviate-labs/hash.mo) - Implements the 32-bit cyclic redundancy check, or CRC-32, checksum.
- [motoko-sha2](https://github.com/timohanke/motoko-sha2) - All hash functions from the SHA2 family (sha224, sha256, sha512-224, sha512-256, sha384, sha512).
- [motoko-sha](https://github.com/enzoh/motoko-sha) - This package implements secure hash algorithms for the Motoko programming language.
- [motoko-SHA](https://github.com/aviate-labs/crypto.mo) - SHA224 and SHA256 hash algorithms as defined in FIPS 180-4.
- [motoko-sha224](https://github.com/flyq/motoko-sha224) - A Sha224 implements for Motoko.
- [rand](https://github.com/aviate-labs/rand.mo) - Pseudo Random Number Generators.

### Data structures

- [array](https://github.com/aviate-labs/array.mo) - Extended Array Package for Motoko.
- [motoko-base](https://github.com/dfinity/motoko-base) - The Motoko base library, commonly used data structures and algorithms, maintained by the official.
- [motoko-bigsearch](https://github.com/matthewhammer/motoko-sequence/blob/2b7b429224/service/BigSearch.mo) - A search service in Motoko, inspired by indexing and search systems like Apache Lucene.
- [motoko-BiMap](https://github.com/aviate-labs/bimap.mo) - A bimap (or "bidirectional map") is a map that preserves the uniqueness of its values as well as that of its keys.
- [motoko-crud](https://github.com/matthewhammer/motoko-crud) - A framework for constructing CRUD services in Motoko for the Internet Computer.
- [motoko_datetime](https://github.com/edjcase/motoko_datetime) - Datetime library. Support for UTC, local timezones, locales and basic datetime operations/structures
- [motoko-MerkleTree](https://github.com/nomeata/motoko-merkle-tree) - A simple merkle tree data structure for Motoko. It provides a key-value store, where both keys and values are of type Blob.
- [motoko-Queue](https://github.com/aviate-labs/queue.mo) - A collection of elements that are maintained in a sequence, a FIFO Queue.
- [motoko-sequence](https://github.com/matthewhammer/motoko-sequence) - Cache-friendly, persistent sequential data for Motoko.
- [motoko-StableMap](https://github.com/mix-labs/StableMap) - Stable Map for the Motoko.
- [MotokoStableBTree](https://github.com/sardariuss/MotokoStableBTree) – Stable Memory Based BTree.
- [motoko-text-map](https://github.com/kritzcreek/motoko-text-map) - A Motoko Hashmap that fixes its key type to Text.
- [mutable-queue.mo](https://github.com/ninegua/mutable-queue.mo) - Motoko module of a mutable queue data structure.
- [Principal](https://github.com/aviate-labs/principal.mo) - Provides a wrapper around the [base principal module](https://github.com/dfinity/motoko-base/blob/master/src/Principal.mo).
- [Stable BTree Map](https://github.com/canscale/StableHeapBTreeMap) - Stable (Heap-based) BTreeMaps in Motoko.
- [Stable Buffers](https://github.com/canscale/StableBuffer) - Stable (Heap-based) Buffers in Motoko.
- [Stable Data Struct](https://github.com/aviate-labs/stable.mo) - Stable (Heap-based) Hashmap implements.
- [Stable HashMaps](https://github.com/canscale/StableHashMap) - Functional & Class-Based (Heap-based) stable Hashmaps in Motoko.
- [Stable LinkedList](https://github.com/canscale/LinkedList) - (Heap-based) Stable, mutable singly & doubly linked lists in Motoko.
- [Stable Red-Black Trees](https://github.com/canscale/StableRBTree) - (Heap-based) Stable Red-Black Trees in Motoko.

### Encoding

- [Account.mo](https://github.com/dfinity/ICRC-1/blob/main/ref/Account.mo) – ICRC1 Account En/Decoding
- [json package](https://github.com/aviate-labs/json.mo) - JSON for Motoko.
- [lexicographic-encoding](https://github.com/canscale/lexicographic-encoding) - Lexicographic (string sortable) integer encoding in Motoko.
- [motoko-base32](https://github.com/flyq/motoko-base32) - Base32 coding/decoding for Motoko.
- [motoko_candid](https://github.com/edjcase/motoko_candid) - CANDID encoding/decoding library
- [motoko_cbor](https://github.com/edjcase/motoko_cbor) - CBOR encoding/decoding library
- [motoko-Encode](https://github.com/aviate-labs/encoding.mo) - Base32, Hex and Binary Library for the Motoko.
- [motoko-hex](https://github.com/enzoh/motoko-hex) - This package implements hexadecimal encoding and decoding routines for the Motoko programming language.
- [motoko-json](https://github.com/kritzcreek/motoko-json) - Json parser in Motoko.
- [motoko-UUID](https://github.com/aviate-labs/uuid.mo) - Generation of UUIDs based on RFC 4122.
- [motoko_xml](https://github.com/edjcase/motoko_xml) - XML encoding/decoding library

### Graphics

- [motoko-graph](https://github.com/matthewhammer/motoko-graph) - Graphical data models for Motoko.
- [motoko-redraw](https://github.com/matthewhammer/motoko-redraw) - 2D graphics and layout algorithms for Motoko.
- [motoko-SVG Generator](https://github.com/aviate-labs/svg.mo) - A SVG generator for the Motoko.

### Logging

- [ic-logger](https://github.com/ninegua/ic-logger) - Motoko library to help create an append-only logger actor.
- [motoko-pretty](https://github.com/kritzcreek/motoko-pretty) - A pretty printer library for Motoko.

### Misc

- [Gitcoin Passport Client](https://github.com/vporton/passport-client-dfinity) - A sample app to securely copy Gitcoin Passport scores to ICP databases.

### Payment

- [IC-PayPortal](https://github.com/Expeera/IC-PayPortal/tree/phase-3) - Module for Motoko is a library that provides developers with a set of functions for managing fiat payments (Stripe, PayPal) on the Internet Computer Protocol (ICP).

### Storage

- [A site about Motoko databases and related software](https://internet-computer.vporton.name)
- [Asset Storage](https://github.com/aviate-labs/asset-storage.mo) - Interface of the Asset Storage Canister.
- [motoko-GraphQL](https://github.com/aviate-labs/graphql.mo) - GraphQL is a query language designed to build client applications and system for describing their data requirements and interactions.
- [Bucket](https://github.com/PrimLabs/Bucket) - A data bucket library that use stable memory to store files bytes and assist developers to build http response.

### Templates

- [motoko-library-template](https://github.com/kritzcreek/motoko-library-template) - A template for creating Motoko libraries.

### Text processing

- [Format](https://github.com/aviate-labs/fmt.mo) - Implements conversions to and from textual representations of basic data types.
- [motoko-regex](https://github.com/kritzcreek/motoko-regex) - Simple regex matching for Motoko Text.
- [motoko-regex-engine](https://github.com/demali-876/motoko_regex_engine)- A library for native pattern matching on the Internet Computer.

### Web Programming

- [Http Request Parser](https://github.com/tomijaga/http-parser.mo) - A http request parser for parsing url, search query, headers and form data.

## Registries

A registry allows you to publish your Rust libraries as crate packages, to share them with others publicly and privately.

- [io package](https://github.com/aviate-labs/io.mo) - Basic Interfaces for I/O Primitives.
- [MOPS](https://j4mwm-bqaaa-aaaam-qajbq-cai.ic0.app/) - A package manager for Motoko with on-chain package registry.
- [Package Set](https://github.com/aviate-labs/package-set) - Aviate-labs package-set for Motoko libraries to use with vessel.
- [Vessel Package Set](https://github.com/dfinity/vessel-package-set) - The official package-set for Motoko libraries to use with vessel.

## Resources

- Learning
  - [AgorApp](https://agorapp.dev/course/learn-motoko) - AgorApp is an online interactive coding platform that provides courses and coding challenges on all-things-web3 engineering and Internet Computer development.
  - [DFINITY Education](https://github.com/orgs/DFINITY-Education/) - Lessons about blockchain, cryptocurrencies and protocol of Internet Computer.
  - [Introducing the Internet Computer](https://smartcontracts.org/docs/introduction/welcome.html) - A comprehensive series of documents that introduce Internet Computer.
  - [Motoko Bootcamp](https://github.com/motoko-bootcamp/education) - Lectures and resources from the Motoko Bootcamp.
  - [motoko by example](https://github.com/dfinity/examples/tree/master/motoko) - An officially maintained collection of short Motoko examples.
  - [The Motoko Programming Language Book](https://web3.motoko-book.dev/) - A guide for writing Web3 Software on the Internet Computer.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
