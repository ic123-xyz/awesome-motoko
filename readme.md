# Awesome Motoko [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> An awesome list of Motoko code and resources curated by the community.


## Contents

- [Applications](#applications)
  - [Canister tools](#canister-tools)
  - [Cryptocurrencies](#cryptocurrencies)
  - [Games](#games)
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
  - [Text processing](#text-processing)
- [Registries](#registries)
- [Resources](#resources)
- [Contribute](#contribute)
- [License](#license)


## Applications

Fully functional smart contract.

### Canister tools

- [candid-spaces](https://github.com/matthewhammer/candid-spaces) - A general-purpose candid data lake for canisters' data on the IC.
- [ic-blackhole](https://github.com/ninegua/ic-blackhole) - Once a canister sets its only controller to a black hole, it becomes immutable and more!
- [motoko_top_up_canister](https://github.com/ORIGYN-SA/motoko_top_up_canister) - Implementation of a canister called periodically by a Node.js service; that top-up automatically user-defined canisters with cycles.
### Cryptocurrencies

- [extendable-token](https://github.com/Toniq-Labs/extendable-token) - This token standard provides a ERC1155/multi-token-like approach with extensions that can add additional functionality based on the purpose of the token. 
- [ic-nft](https://github.com/rocklabs-io/ic-nft) - A NFT standard implementation for the Internet Computer, the interfaces mainly follow the ERC721 standard.
- [ic-token](https://github.com/rocklabs-io/ic-token) - An ERC-20 style token standard implements for Motoko.
- [motoko-token](https://github.com/enzoh/motoko-token) - This package implements a simple ERC-20 style token.

### Games

- [reversi](https://github.com/ninegua/reversi) — Multiplayer Reversi Game on [Internet Computer](https://dfinity.org).

### Social

- [LinkedUp](https://github.com/dfinity/linkedup) - An open professional network.

### Storage

- [motoko-dht](https://github.com/enzoh/motoko-dht) - This canister implements a distributed hash table.
- [motoko-cdn](https://github.com/gabrielnic/motoko-cdn) - A simple storage auto-scaling solution across multiple canisters. Ie: mini-bigmap.

### Utilities

- [motoko-certified-http](https://github.com/nomeata/motoko-certified-http) - A motoko canister that does HTTP asset certification.
- [cleansheets](https://github.com/matthewhammer/cleansheets) - A spreadsheet-like application for the Internet Computer, written in Motoko.

### Video

- [cancan](https://github.com/dfinity/cancan) - A scalable video-sharing service.

## Development tools

### Build system

- [dfx](https://github.com/dfinity/sdk/tree/master/src/dfx) - The DFINITY command-line execution environment (dfx) is the primary tool for creating, deploying, and managing the dapps you develop for the Internet Computer blockchain.
- [Vessel package manager](https://github.com/dfinity/vessel) - Add and manage packages, libraries, and dependencies for your Motoko programs.

### IDEs

- [Visual Studio Code](https://code.visualstudio.com/)
  - [Motoko](https://marketplace.visualstudio.com/items?itemName=dfinity-foundation.vscode-motoko) - Motoko language support.
- [IntelliJ IDEA Motoko support](https://github.com/ununhexium/idea-motoko-plugin) - Adds support for the Motoko language from Dfinity.
- [motoko-playground](https://github.com/dfinity/motoko-playground) - A playground for the Internet Computer's native Motoko language.

### Testing

- [motoko-bigtest](https://github.com/matthewhammer/motoko-bigtest) - Long-running tests as/for IC services, via a Motoko-based DSL.
- [motoko-matchers](https://github.com/kritzcreek/motoko-matchers) - Composable assertions for unit testing.
  - [ic101](https://github.com/kritzcreek/ic101) - This repository demonstrates how to use the [matchers](https://github.com/kritzcreek/motoko-matchers) library to unit test canisters on the Internet Computer.
- [ic-mini-terminal](https://github.com/matthewhammer/ic-mini-terminal) - Minimal keyboard input (⌨) and graphical output (📺) for programs on the Internet Computer.
## Libraries

### Templates

- [motoko-library-template](https://github.com/kritzcreek/motoko-library-template) - A template for creating Motoko libraries.
- [motoko-crud](https://github.com/matthewhammer/motoko-crud) - A framework for constructing CRUD services in Motoko for the Internet Computer.
- [superheroes](https://github.com/enzoh/superheroes) - A simple example that demonstrates how to build a CRUD application on the Internet Computer using Motoko and React.

### Algorithms

- [chronosphere](https://github.com/enzoh/chronosphere) - A time library for the Motoko programming language.
- [motoko-adapton](https://github.com/matthewhammer/motoko-adapton) - Dynamic dependence graph and memoization techniques in Motoko.
- [motoko-crc](https://github.com/enzoh/motoko-crc) - This package implements cyclic redundancy checks for the Motoko programming language.
- [motoko-qr](https://github.com/enzoh/motoko-qr) - A QR-code generator for the Motoko programming language.
- [motoko-scc](https://github.com/nomeata/motoko-scc) - A Strongly Connected Component library for Motoko.
- [motoko-splay](https://github.com/chenyan2002/motoko-splay) - The splaying algorithm for Motoko.
- [mo-parsec](https://github.com/crusso/mo-parsec) - A [Parsec](https://hackage.haskell.org/package/parsec)-based parser combinator library for Motoko.
- [motoko-crc](https://github.com/enzoh/motoko-crc) - This package implements cyclic redundancy checks for the Motoko programming language.

### Cryptography

- [motoko-sha](https://github.com/enzoh/motoko-sha) - This package implements secure hash algorithms for the Motoko programming language.
- [motoko-sha224](https://github.com/flyq/motoko-sha224) - A Sha224 implements for Motoko.

### Data structures

- [motoko-base](https://github.com/dfinity/motoko-base) - The motoko base library, commonly used data structures and algorithms, maintained by the official.
- [motoko-bigsearch](https://github.com/matthewhammer/motoko-sequence/blob/2b7b429224/service/BigSearch.mo) - A search service in Motoko, inspired by indexing and search systems like Apache Lucene.
- [motoko-crud](https://github.com/matthewhammer/motoko-crud) - A generic CRUD framework for Motoko.
- [motoko-MerkleTree](https://github.com/nomeata/motoko-merkle-tree) - A simple merkle tree data structure for Motoko. It provides a key-value store, where both keys and values are of type Blob.
- [motoko-sequence](https://github.com/matthewhammer/motoko-sequence) - Cache-friendly, persistent sequential data for Motoko.
- [motoko-StableMap](https://github.com/mix-labs/StableMap) - Stable Map for the Motoko.
- [motoko-text-map](https://github.com/kritzcreek/motoko-text-map) - A Motoko Hashmap that fixes its key type to Text.
### Encoding

- [motoko-base32](https://github.com/flyq/motoko-base32) - Base32 cod for Motoko
- [motoko-hex](https://github.com/enzoh/motoko-hex) - This package implements hexadecimal encoding and decoding routines for the Motoko programming language.
- [motoko-json](https://github.com/kritzcreek/motoko-json) - Json parser in Motoko.

### Graphics

- [motoko-graph](https://github.com/matthewhammer/motoko-graph) - Graphical data models for Motoko.
- [motoko-redraw](https://github.com/matthewhammer/motoko-redraw) - 2D graphics and layout algorithms for Motoko.

### Logging

- [motoko-pretty](https://github.com/kritzcreek/motoko-pretty) - A pretty printer library for Motoko.

### Text processing

- [motoko-regex](https://github.com/kritzcreek/motoko-regex) - Simple regex matching for Motoko Text.

## Registries

A registry allows you to publish your Rust libraries as crate packages, to share them with others publicly and privately.

- [Vessel Package Set](https://github.com/dfinity/vessel-package-set) - The official community package-set for Motoko libraries to use with [vessel](https://github.com/dfinity/vessel).

## Resources

- Learning
  - [Introducing the Internet Computer](https://smartcontracts.org/docs/introduction/welcome.html) - A comprehensive series of documents that introduce Internet Computer.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
