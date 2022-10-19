# Awesome Solana

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated (unofficial) list of resources for builders / artists hacking on Solana.

* Includes: open standards, protocols, open source repos, community-built tools
* Ordering: open source before closed source, ordered by github stars

If you see something missing - please submit a PR 🙏

_Heavily_ onspired by:
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

## Solana VM Blockchains

- [Solana](https://github.com/solana-labs/solana) is the current monorepo containing the Solana Virtual Machine code (under active development & improvement)
- [Nitro SVM](https://mobile.twitter.com/nitro_labs) is the first Solana VM chain (built on Cosmos).
- [Eclipse](https://eclipse.builders/) is the first service providing customizable modular rollups, using the Solana VM

## Books and Tutorials

- [Solana Cookbook](https://solanacookbook.com/) is a developer resource that provides the essential concepts and references for building applications on Solana
- [Anchor Lang Book](https://book.anchor-lang.com/) teaches how to build Solana programs using the Anchor framework
- [SolDev Tutorials](https://soldev.app/)

## Jobs

- [Solana Ecosystem Job Board](https://jobs.solana.com/jobs)
- [Earn.Superteam](https://earn.superteam.fun/)

## Block Explorers

- [Official Solana Explorer](https://explorer.solana.com/)
- [Solana FM](https://solana.fm/)
- [Solscan](https://solscan.io/)

## Code

See the [official developers page](https://solana.com/developers) for official resources.

Got a question? Ask away on [the official Solana Stackexchange](https://solana.stackexchange.com/).

### NFTs

- [Metaplex](https://github.com/metaplex-foundation/metaplex-program-library/)
    ![](https://img.shields.io/github/stars/metaplex-foundation/metaplex.svg?style=social)
    ([docs](https://docs.metaplex.com/architecture/deep_dive/metaplex)) Metaplex is a set of progams that together enable NFT creators to mint, auction, airdrop, and update NFTs (and more!)
- [NFToken](https://github.com/glow-xyz/nftoken) ![](https://img.shields.io/github/stars/glow-xyz/nftoken.svg?style=social) ([docs](https://nftoken.so/docs/overview)) NFToken is a simple, cheap NFT standard for Solana by Glow Wallet

### Defi

- [Serum Monorepo](https://github.com/project-serum/serum-dex) ![](https://img.shields.io/github/stars/project-serum/serum-dex.svg?style=social) Project Serum Rust Monorepo. Serum was the first Central Limit Order Book (CLOB) on Solana, and has been a cornerstone of Solana Defi.
- [Mango Markets V3](https://github.com/blockworks-foundation/mango-v3) ![](https://img.shields.io/github/stars/blockworks-foundation/mango-v3.svg?style=social)
- [Jet Protocol V2](https://github.com/jet-lab/jet-v2) ![](https://img.shields.io/github/stars/jet-lab/jet-v2.svg?style=social) Implementation of the Jet Protocol V2 programs for Solana

### On-Chain Governance

- [SPL Governance](https://github.com/solana-labs/solana-program-library/tree/master/governance) ![](https://img.shields.io/github/stars/solana-labs/solana-program-library.svg?style=social) SPL Governance is a program the chief purpose of which is to provide core building blocks and primitives to create Decentralized Autonomous Organizations (DAOs) on Solana blockchain. [Realms](https://realms.today/) is the official UI for interacting with organizations running on top of SPL Governance. The UI is [open sourced](https://github.com/solana-labs/governance-ui) ![](https://img.shields.io/github/stars/solana-labs/governance-ui.svg?style=social).

### Cross-Chain Bridge

- [Wormhole](https://github.com/wormhole-foundation/wormhole) ![](https://img.shields.io/github/stars/wormhole-foundation/wormhole.svg?style=social) A reference implementation for the Wormhole blockchain interoperability protocol. See more information about [wormhole here](https://wormhole.com/).

### Social

- [Wordcel](https://github.com/Wordcel/wordcel) ![](https://img.shields.io/github/stars/Wordcel/wordcel.svg?style=social) V1 of the Wordcel social protocol, with emphasis on long-form blogging at the moment

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
- [solanaj](https://github.com/p2p-org/solanaj) ![](https://img.shields.io/github/stars/p2p-org/solanaj.svg?style=social) Solana blockchain client, written in pure Java.
- [Solders](https://github.com/kevinheavey/solders) ![](https://img.shields.io/github/stars/kevinheavey/solders.svg?style=social) Python wrapper for Rust SDK

## IDEs

- [Online Solana IDE - Solana Playground](https://beta.solpg.io/) [code](https://github.com/solana-playground/solana-playground) ![](https://img.shields.io/github/stars/solana-playground/solana-playground.svg?style=social)
- [VSCode Plugin for Anchor](https://marketplace.visualstudio.com/items?itemName=Ayushh.vscode-anchor) [code](https://github.com/heyAyushh/vscode-solana) ![](https://img.shields.io/github/stars/heyAyushh/vscode-solana.svg?style=social)

## Wallets 

Please note that the following is an **_unofficial_** list ordered as described above:

- [Coral-xyz's Backpack](https://github.com/coral-xyz/backpack) ![](https://img.shields.io/github/stars/coral-xyz/backpack.svg?style=social) Cross chain wallet for Solana and Ethereum, it's specialty is its app store, which allows dApps to be bought as xNFTs (executable NFTs) which can then be run inside your wallet
- [Solana Wallet for Unity](https://github.com/allartprotocol/unity-solana-wallet) ![](https://img.shields.io/github/stars/allartprotocol/unity-solana-wallet.svg?style=social) The First Open-Source Unity-Solana Wallet with NFT support
- [p2p's Web Wallet](https://github.com/p2p-org/p2p-wallet-web) ![](https://img.shields.io/github/stars/p2p-org/p2p-wallet-web.svg?style=social) An Open Source Browser Based Solana Wallet.


## Security

- [Solana Status](https://status.solana.com/) shows the health of the Solana mainnet cluster & RPC nodes
- [Official Solana News](https://solana.com/news/)


## Contributing

Contributions are received with 💜
