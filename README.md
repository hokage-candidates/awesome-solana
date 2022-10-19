# Awesome Solana

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated (unofficial) list of resources for builders / artists hacking on Solana.

* Includes: open standards, protocols, open source repos, community-built tools
* Ordering: open source before closed source, ordered by github stars

If you see something missing - please submit a PR 🙏

_Heavily_ inspired by:
* [Illmoi's Awesome Solana NFTs](https://github.com/ilmoi/awesome-solana-nfts)
* [Paul Schaaf's Awesome Solana](https://github.com/paul-schaaf/awesome-solana)

Table of Contents
=================
* [Overview](#overview)
* [Solana VM Blockchains](#solana-vm-blockchains)
* [Books and Tutorials](#books-and-tutorials)
* [Jobs](#jobs)
* [Block Explorers](#block-explorers)
* [Code](#code)
  * [Non-Fungible Tokens (NFTs)](#nfts)
  * [Decentralized Finance (Defi)](#defi)
  * [On-chain Governance](#on-chain-governance)
  * [Cross-Chain Bridge](#cross-chain-bridge)
  * [Oracles](#oracles)
  * [Social](#social)
  * [Frameworks](#frameworks)
  * [Libraries](#libraries)
  * [Indexers](#indexers)
* [IDEs](#ides)
* [Wallets](#wallets)
* [Security](#security)

## Overview

- [Install the Official Solana CLI](https://docs.solana.com/cli/install-solana-cli-tools)
- [Developer Guide](https://docs.solana.com/developers)
- [Anchor's Intro to Solana](https://www.anchor-lang.com/docs/intro-to-solana)
- [Intro to Solana for Solidity Developers]( https://2501babe.github.io/posts/solana101.html)

## Solana VM Blockchains

- [Solana](https://github.com/solana-labs/solana) is the current monorepo containing the Solana Virtual Machine code (under active development & improvement)
- [Nitro SVM](https://mobile.twitter.com/nitro_labs) is the first Solana VM chain (built on Cosmos).
- [Eclipse](https://eclipse.builders/) is the first service providing customizable modular rollups, using the Solana VM

## Books, Tutorials, and Courses

- [Solana Cookbook](https://solanacookbook.com/) is a developer resource that provides the essential concepts and references for building applications on Solana
- [Anchor Lang Book](https://book.anchor-lang.com/) teaches how to build Solana programs using the Anchor framework
- [SolDev Tutorials](https://soldev.app/)
- [Buildspace Tutorials](https://buildspace.so/learn-solana)
- [Guide to Fullstack Development on Solana](https://dev.to/dabit3/the-complete-guide-to-full-stack-solana-development-with-react-anchor-rust-and-phantom-3291)

Official Solana Developer Resources:
- [Bootcamp Lectures - Highly Technical](https://github.com/solana-developers/solana-bootcamp-lectures) ![](https://img.shields.io/github/stars/solana-developers/solana-bootcamp-lectures.svg?style=social)
- [Program Examples](https://github.com/solana-developers/program-examples) ![](https://img.shields.io/github/stars/solana-developers/program-examples.svg?style=social)
- [Workshop dApps](https://github.com/solana-developers/workshop-dapps) ![](https://img.shields.io/github/stars/solana-developers/workshop-dapps.svg?style=social)

Figment Courses:
- [Fullstack mail dApp on Solana](https://learn.figment.io/tutorials/create-a-fullstack-mail-dapp-on-solana)
- [Crowdfunding with Solana](https://learn.figment.io/tutorials/crowdfunding-with-solana)
- [Make a Solana Explorer Clone Using React](https://learn.figment.io/tutorials/make-a-solana-explorer-clone-using-react)

SolHack Courses:
- [Building Solana Smart Contract dApps](https://solhack.com/courses/building-solana-smart-contracts-dapps-with-james-bachini/)
- [Programming on Solana](https://solhack.com/courses/programming-on-solana-an-introduction/)

## Jobs

- [Solana Ecosystem Job Board](https://jobs.solana.com/jobs)
- [Superteam DAO's Earn Page](https://earn.superteam.fun/)

## Block Explorers

- [Official Solana Explorer](https://explorer.solana.com/)
- [Solana FM](https://solana.fm/)
- [Solscan](https://solscan.io/)

## Code

See the [official developers page](https://solana.com/developers) for official resources.

Got a question? Ask away on [the official Solana Stackexchange](https://solana.stackexchange.com/).

### NFTs

For a much more extensive list of information regarding Solana NFTs, please see [awesome-solana-nfts](https://github.com/ilmoi/awesome-solana-nfts/blob/main/README.md). The following focuses on open-source core protocols related to NFT development on Solana.

- [Metaplex](https://github.com/metaplex-foundation/metaplex-program-library/)
    ![](https://img.shields.io/github/stars/metaplex-foundation/metaplex.svg?style=social)
    ([docs](https://docs.metaplex.com/architecture/deep_dive/metaplex)) Metaplex is a set of progams that together enable NFT creators to mint, auction, airdrop, and update NFTs (and more!)
- [Cardinal Lab's Token Manager](https://github.com/cardinal-labs/cardinal-token-manager) ![](https://img.shields.io/github/stars/cardinal-labs/cardinal-token-manager.svg?style=social) Cardinal token manager is a set of smart contracts on Solana to facilitate conditionally managed ownership. Using the invalidators and approvers in various ways allows for building rentals, expiring in-game items, subscriptions, permits, tickets, passes and more.
- [NFToken](https://github.com/glow-xyz/nftoken) ![](https://img.shields.io/github/stars/glow-xyz/nftoken.svg?style=social) ([docs](https://nftoken.so/docs/overview)) NFToken is a simple, cheap NFT standard for Solana by Glow Wallet

### Defi

Token Protocols:
- [SPL Token](https://github.com/solana-labs/solana-program-library/tree/master/token) ![](https://img.shields.io/github/stars/solana-labs/solana-program-library.svg?style=social) Similar to [ERC-20 standard](https://ethereum.org/en/developers/docs/standards/tokens/erc-20/)
- [SPL Token 2022](https://github.com/solana-labs/solana-program-library/tree/master/token/program-2022) ![](https://img.shields.io/github/stars/solana-labs/solana-program-library.svg?style=social) Not yet widely adopted

Defi Protocols:
- [Serum Monorepo](https://github.com/project-serum/serum-dex) ![](https://img.shields.io/github/stars/project-serum/serum-dex.svg?style=social) Project Serum Rust Monorepo. Serum was the first Central Limit Order Book (CLOB) on Solana, and has been a cornerstone of Solana Defi.
- [Saber Stable Swap](https://github.com/saber-hq/stable-swap) ![](https://img.shields.io/github/stars/saber-hq/stable-swap.svg?style=social) 🔁 StableSwap by Saber: an automated market maker for mean-reverting trading pairs.
- [Bonfida Token Vesting](https://github.com/Bonfida/token-vesting) ![](https://img.shields.io/github/stars/Bonfida/token-vesting.svg?style=social) A Vesting Contract for the Solana Blockchain
- [Mango Markets V3](https://github.com/blockworks-foundation/mango-v3) ![](https://img.shields.io/github/stars/blockworks-foundation/mango-v3.svg?style=social) One of the largest Solana margin trading platforms
- [Jet Protocol V2](https://github.com/jet-lab/jet-v2) ![](https://img.shields.io/github/stars/jet-lab/jet-v2.svg?style=social) Implementation of the Jet Protocol V2 programs for Solana
- [Marinade Finance Liquid Staking Program](https://github.com/marinade-finance/liquid-staking-program) ![](https://img.shields.io/github/stars/marinade-finance/liquid-staking-program.svg?style=social)

Canonical open source examples:
- [SPL Token Lending](https://github.com/solana-labs/solana-program-library/tree/master/token-lending) ![](https://img.shields.io/github/stars/solana-labs/solana-program-library.svg?style=social) A lending protocol for the Token program on the Solana blockchain inspired by Aave and Compound
- [SPL Token Swap](https://github.com/solana-labs/solana-program-library/tree/master/token-swap) ![](https://img.shields.io/github/stars/solana-labs/solana-program-library.svg?style=social) A Uniswap-like exchange for the Token program on the Solana blockchain.


### On-Chain Governance

- [SPL Governance](https://github.com/solana-labs/solana-program-library/tree/master/governance) ![](https://img.shields.io/github/stars/solana-labs/solana-program-library.svg?style=social) SPL Governance is a program the chief purpose of which is to provide core building blocks and primitives to create Decentralized Autonomous Organizations (DAOs) on Solana blockchain. [Realms](https://realms.today/) is the official UI for interacting with organizations running on top of SPL Governance. The UI is [open sourced](https://github.com/solana-labs/governance-ui) ![](https://img.shields.io/github/stars/solana-labs/governance-ui.svg?style=social).

### Cross-Chain Bridge

- [Wormhole](https://github.com/wormhole-foundation/wormhole) ![](https://img.shields.io/github/stars/wormhole-foundation/wormhole.svg?style=social) A reference implementation for the Wormhole blockchain interoperability protocol. See more information about [wormhole here](https://wormhole.com/).

### Oracles

- [Switchboard](https://github.com/switchboard-xyz/switchboard-v2) ![](https://img.shields.io/github/stars/switchboard-xyz/switchboard-v2.svg?style=social) ([docs](https://docs.switchboard.xyz/)) Switchboard provides a permission-less data layer to bridge the gap between the internet and web3.
- [Pyth Oracles for Serum Order Book Prices](https://github.com/pyth-network/pyth-serum) and it's [Rust SDK](https://github.com/pyth-network/pyth-sdk-rs). See more information about [Pyth Network here](https://pyth.network/).

### Social

- [Strata Protocol](https://github.com/StrataFoundation/strata) ![](https://img.shields.io/github/stars/StrataFoundation/strata.svg?style=social) ([docs](docs.strataprotocol.com)) Strata Protocol is an open-source protocol to launch tokens around a person, project, idea, or collective on Solana
- [Cardinal Lab's Namespaces](https://github.com/cardinal-labs/cardinal-namespaces) ![](https://img.shields.io/github/stars/cardinal-labs/cardinal-namespaces.svg?style=social) Cardinal program for mapping string names to data on-chain. Names are organized into logical groupings called namespaces. Namespaces authority can optionally set a rental price. Names are represented as NFTs wrapped using cardinal-token-manager
- [Wordcel](https://github.com/Wordcel/wordcel) ![](https://img.shields.io/github/stars/Wordcel/wordcel.svg?style=social) V1 of the Wordcel social protocol, with emphasis on long-form blogging at the moment
- [Bonfida's Name Service Guide](https://github.com/Bonfida/solana-name-service-guide) possibly deprecated ?? not sure

### Frameworks

- [Anchor](https://github.com/coral-xyz/anchor) ![](https://img.shields.io/github/stars/coral-xyz/anchor.svg?style=social) ⚓ Solana Sealevel Framework
- [Seahorse](https://github.com/ameliatastic/seahorse-lang) ![](https://img.shields.io/github/ameliatastic/seahorse-lang.svg?style=social) Write Solana programs in Python
- [Solita](https://github.com/metaplex-foundation/solita) ![](https://img.shields.io/github/stars/metaplex-foundation/solita.svg?style=social) Generates an SDK API from solana contract IDL (written by Metaplex to generate typescript SDK from Shank IDL)
- [Shank](https://github.com/metaplex-foundation/shank) ![](https://img.shields.io/github/stars/metaplex-foundation/shank.svg?style=social) Extracts IDL from Solana Rust contracts (written by Metaplex for Metaplex NFT standard)

### Libraries

- [Sokoban](https://github.com/Ellipsis-Labs/sokoban) ![](https://img.shields.io/github/stars/Ellipsis-Labs/sokoban.svg?style=social) Compact, efficient data structures in contiguous byte arrays (for use in Solana smart contracts)

### Indexers

- [Holaplex's NFT Indexer](https://github.com/holaplex/indexer) ![](https://img.shields.io/github/stars/holaplex/indexer.svg?style=social)
- [Metaplex's NFT Indexer](https://github.com/metaplex-foundation/digital-asset-validator-plugin) ![](https://img.shields.io/github/stars/metaplex-foundation/digital-asset-validator-plugin.svg?style=social)

## SDKs

- [Official Web3.js](https://github.com/solana-labs/solana/tree/master/web3.js) ![](https://img.shields.io/github/stars/solana-labs/solana.svg?style=social) Solana JavaScript API
- [Official Rust SDK](https://github.com/solana-labs/solana/tree/master/sdk) ![](https://img.shields.io/github/stars/solana-labs/solana.svg?style=social) Solana Rust SDK
- [Solana.py](https://github.com/michaelhly/solana-py) ![](https://img.shields.io/github/stars/michaelhly/solana-py.svg?style=social) Solana Python SDK
- [Solana Go](https://github.com/gagliardetto/solana-go.git) ![](https://img.shields.io/github/stars/gagliardetto/solana-go.svg?style=social) Solana Web3.js library in Go
- [Solnet](https://github.com/bmresearch/Solnet) ![](https://img.shields.io/github/stars/bmresearch/Solnet.svg?style=social) Solana .NET SDK and integration library
- [Cryptoplease-dart](https://github.com/cryptoplease/cryptoplease-dart) ![](https://img.shields.io/github/stars/cryptoplease/cryptoplease-dart.svg?style=social) Dart and Flutter apps and libraries maintained by Crypto Please team for Solana
- [SolanaKT](https://github.com/metaplex-foundation/SolanaKT) ![](https://img.shields.io/github/stars/metaplex-foundation/SolanaKT.svg?style=social) Solana SDK for Kotlin
- [Solders](https://github.com/kevinheavey/solders) ![](https://img.shields.io/github/stars/kevinheavey/solders.svg?style=social) Python wrapper for Rust SDK
- [solanaj](https://github.com/skynetcap/solanaj) ![](https://img.shields.io/github/stars/p2p-org/solanaj.svg?style=social) Solana blockchain client, written in pure Java

## IDEs

- [Online Solana IDE - Solana Playground](https://beta.solpg.io/) [code](https://github.com/solana-playground/solana-playground) ![](https://img.shields.io/github/stars/solana-playground/solana-playground.svg?style=social)
- [VSCode Plugin for Anchor](https://marketplace.visualstudio.com/items?itemName=Ayushh.vscode-anchor) [code](https://github.com/heyAyushh/vscode-solana) ![](https://img.shields.io/github/stars/heyAyushh/vscode-solana.svg?style=social)

## Wallets 

Please note that the following is an **_unofficial_** list ordered as described above:

- [Coral-xyz's Backpack](https://github.com/coral-xyz/backpack) ![](https://img.shields.io/github/stars/coral-xyz/backpack.svg?style=social) Cross chain wallet for Solana and Ethereum, it's specialty is its app store, which allows dApps to be bought as xNFTs (executable NFTs) which can then be run inside your wallet
- [Solana Wallet for Unity](https://github.com/allartprotocol/unity-solana-wallet) ![](https://img.shields.io/github/stars/allartprotocol/unity-solana-wallet.svg?style=social) The First Open-Source Unity-Solana Wallet with NFT support
- [p2p's Web Wallet](https://github.com/p2p-org/p2p-wallet-web) ![](https://img.shields.io/github/stars/p2p-org/p2p-wallet-web.svg?style=social) An Open Source Browser Based Solana Wallet.

Closed Source Wallets:

- [Phantom](https://phantom.app/)
- [Solflare](https://solflare.com/)
- [Glow](https://glow.app/)


## Security

#### Network-level Resources:
- [Solana Status](https://status.solana.com/) shows the health of the Solana mainnet cluster & RPC nodes
- [Official Solana News](https://solana.com/news/)

#### Program-level Resources

Neodyme:
- [List of Common Security Pitfalls](https://blog.neodyme.io/posts/solana_common_pitfalls)
- [Workshop Tutorial](https://workshop.neodyme.io/)
- [PoC Framework](https://github.com/neodyme-labs/solana-poc-framework) ![](https://img.shields.io/github/stars/neodyme-labs/solana-poc-framework.svg?style=social)

OtterSec
- [Framework for Solana CTF Challenges](https://github.com/otter-sec/sol-ctf-framework) ![](https://img.shields.io/github/stars/otter-sec/sol-ctf-framework.svg?style=social)
- [Binary Ninja Plugin for Solana Byte Format](https://github.com/otter-sec/bn-ebpf-solana) ![](https://img.shields.io/github/stars/otter-sec/bn-ebpf-solana.svg?style=social)
- [Jet Protocol Governance PoCs](https://github.com/otter-sec/jet-governance-pocs) ![](https://img.shields.io/github/stars/otter-sec/jet-governance-pocs.svg?style=social)

Sec3 Dev's Auditing Tutorials:
- [Part One](https://medium.com/coinmonks/how-to-audit-solana-smart-contracts-part-1-a-systematic-approach-56a434f6c9ed)
- [Part Two](https://medium.com/coinmonks/how-to-audit-solana-smart-contracts-part-2-automated-scanning-ceb88830ae6d)
- [Part Three](https://medium.com/coinmonks/how-to-audit-solana-smart-contracts-part-3-penetration-testing-a315b3bbb2d3)

Solend Protocol's Auditing Presentation:
- [Auditing Workshop Slides](https://docs.google.com/presentation/d/1jZ9kVo6hnhBsz3D2sywqpMojqLE5VTZtaXna7OHL1Uk/edit?pli=1#slide=id.ge15c343642_0_51)

## Contributing

Contributions are received with 💜
