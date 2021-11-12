
<h1 align="center"> 
<p align="center">
  <a href="https://gear-tech.io">
    <img src="https://gear-tech.io/images/footer-logo.svg" width="400" alt="GEAR">
  </a>
</p>
The most advanced smart-contract engine
</h1>

<p align="center">
 <img src="images\gear.gif" alt="Snow"><br>
Gear is a Substrate-based smart-contract platform allowing anyone to run dApp in a few minutes.
</p>

# 

<div align="center">

[![CI][c1]][c2]
[![GitHubStars][g1]][g2] 
[![Discord][d1]][d2] 
[![Twitter][t1]][t2] 
[![License][l1]][l2] 

[c1]: https://github.com/gear-tech/gear/workflows/CI/badge.svg
[c2]: https://github.com/gear-tech/gear/actions/workflows/CI.yaml

[g1]: https://img.shields.io/github/stars/gear-tech/gear?style=flat-square&label=Stars
[g2]: https://github.com/gear-tech/gear

[t1]: https://img.shields.io/twitter/follow/gear_techs?style=social
[t2]: https://twitter.com/gear_techs

[d1]: https://img.shields.io/discord/891063355526217738?style=flat-square&label=Discord
[d2]: https://discord.com/invite/7BQznC9uD9

[l1]: https://img.shields.io/badge/License-GPL%203.0-success
[l2]: https://github.com/gear-tech/gear/blob/master/LICENSE
</div>

<h4 align="center">Hit the <a href="https://github.com/gear-tech/gear">:star:</a> button to keep up with our daily progress!</h4>

# 🧐 Why?

The blockchain technology launched a rapid transition from centralized, server-based internet (Web2) to decentralized, distributed one (Web3). 

Web3 introduces a new type of decentralized applications (dApps) that enable the existence of DeFi, DEX, Decentralized marketplaces, NFTs, Creators and Social Tokens.

Smart Contract is an equivalent of a microservice which is stored on the blockchain network and is the essential building block of a decentralized application.

Modern blockchains solve many issues of the older blockchain networks, such as:
 - Lack of scalability, low transaction speed, high transaction costs
 - Domain-specific development language (high barrier to entry)
 - Complex and inefficient native consensus protocols
 - Absence of intercommunication tools

But still have room for improvements due to:
 - Fixated, rigid native consensus protocols
 - Lack of interoperability with other networks

To resolve the interoperability issue, Parity technologies focused on creating a technology that connects every other blockchain: 
  - Polkadot - a blockchain of blockchains. Provides a “relay chain” (the primary blockchain) that allows “parachains” (functional blockchains) to be deployed on top of it. All parachains are interconnected, creating a massive network of multifunctional blockchain services.
  - Substrate - a modular framework that allows to create custom-built blockchains with consensus mechanism, core functionality and security out of the box.

Building a blockchain with Substrate allows it to be deployed on any compatible relay chain such as Polkadot and Kusama
Substrate serves as a layer of communication between the relay chain and the parachain

# ⚙️ What does Gear do?

<style>
td, th {
   border: none!important;
}
</style>

| | |
|:--:|:--:|
|<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/Rust_programming_language_black_logo.svg/440px-Rust_programming_language_black_logo.svg.png" height="64"><br>Gear provides the easiest and most cost-effective way to run WebAssembly programs (smart-contracts) compiled from many popular languages, such as Rust, C/C++ and more.|<img src="https://cdn-icons.flaticon.com/png/512/2721/premium/2721620.png?token=exp=1636710308~hmac=3f034973f41e21445556a8423cdb5d11" height="64"><br>Gear ensures very minimal, intuitive, and sufficient API for running both newly written and existing programs on multiple networks without the need to rewrite them.|
|<img src="https://cdn-icons.flaticon.com/png/512/3114/premium/3114998.png?token=exp=1636710881~hmac=e592322aee3b6cee39aeb0b2703e6782" height="64"><br>Smart Contracts are stored in the blockchain’s state and are invoked preserving their state upon request.|<img src="https://cdn-icons-png.flaticon.com/512/3063/3063668.png" height="64"><br>GEAR enables a seamless transition to Web3, alows running dApps, microservices, middleware, open APIs.|


### Key features

 - Programs run in WASM WM (near-native code execution speed)
 - **Unique**: Parallelizable architecture (even greater speed)
 - **Unique**: Actor model for message-passing communications - secure, effective, clear
 - dApp in minutes using GEAR libraries
 - Based on Substrate

### Main capabilities

Gear allows anyone to create and run any custom-logic dApp and is a go-to solution for the following types of applications:
  - A **self-contained blockchain** network (and very fast).
  - A standalone instance running microservices, middleware, open API and more
  - Being a **Polkadot parachain**, establish cross-chain communications between other blockchains. Allow anyone to run a dApp in the Polkadot network in a very **cost-less** manner.
  - Join Substrate-supported blockchains in any other platform outside Polkadot.

# 🏭 How does it work?

<div style="position: relative;">
  <img src="images\internal_flow.png" alt="Snow" style="width:100%;">
  <div style="position: absolute; top: 8px; left: 16px">The internal flow of Gear
  </div>
</div>
Refer to the <a href="https://github.com/gear-tech/gear-technical/blob/master/TECHNICAL.pdf">technical paper</a> for some insights about how Gear works internally.

# Gear components

* [core](https://github.com/gear-tech/gear/tree/master/core) - Gear engine for distributed computing core components.

* [node](https://github.com/gear-tech/gear/tree/master/node) - Gear substrate-based node, ready for hacking :rocket:.

* [gstd](https://github.com/gear-tech/gear/tree/master/gstd) - Standard library for Gear smart contracts.

* [examples](https://github.com/gear-tech/gear/tree/master/examples) - Gear smart contract examples.


# <img style="vertical-align:middle" src="https://seeklogo.com/images/F/For_Dummies-logo-270963AFD1-seeklogo.com.png" width="40" alt="get-start"> Getting Started

1. To start familiarity with Gear, download and run Gear node connected to the testnet.

2. Build your smart-contract into WASM 

2. Deploy and test smart contract, check how it is going. A comprehensive amount of smart contract examples is available for your convenience and faster onboarding.

## <img style="vertical-align:middle" src="https://miro.medium.com/max/256/0*85Brxv3Qe4ps_A6C" width="40" alt="run-node"> Run Gear Node

....Some node Badge...?

1. Download nightly build of Gear node:

    - **Windows x64**: [gear-nightly-windows-x86_64.zip](https://builds.gear.rs/gear-nightly-windows-x86_64.zip)
    - **macOS M1**: [gear-nightly-macos-m1.tar.gz](https://builds.gear.rs/gear-nightly-macos-m1.tar.gz)
    - **macOS Intel x64**: [gear-nightly-macos-x86_64.tar.gz](https://builds.gear.rs/gear-nightly-macos-x86_64.tar.gz)
    - **Linux x64**: [gear-nightly-linux-x86_64.tar.xz](https://builds.gear.rs/gear-nightly-linux-x86_64.tar.xz)

2. Run Gear node without special arguments to get a node connected to the testnet:

    ```bash
    gear-node
    ```

3. Get more info about usage details, flags, avilable options and subcommands:

    ```bash
    gear-node --help
    ```

Gear node can run in a single Dev Net mode or you can create a Multi-Node local testnet or make your own build of Gear node.

Refer to the [Gear Node README](https://github.com/gear-tech/gear/tree/master/node) for details and some examples.

## <img style="vertical-align:middle" src="https://www.clipartmax.com/png/full/37-379882_smart-contract-vulnerability-smart-contracts-blockchain-icon.png" width="40" alt="run-node"> Run you first smart contract

Prepare your program
1. Choose an example program from [examples](https://github.com/gear-tech/gear/tree/master/examples) or use your own program
2. Follow the [instruction](https://github.com/gear-tech/gear/blob/master/examples/README.md) to build the Rust to WebAssembly program
    
### Upload program from UI
    
1. Go to [https://idea.gear-tech.io](https://idea.gear-tech.io)
<img style="vertical-align:middle" src="..." width="40" alt="get-start">
Screenoshot / GIF

2. Sign in to Gear via Telegram or Github account

3. Connect to your node:
    1. TBD

4. Click **Upload program** and choose compiled .wasm file to upload
    1. Set enough Gas limit - 1 000 000
    2. Intial parameters, Initial value - keep default
    3. Upload file with Metadata, if applicable
        1. the file can be found after program compilation from available examples
    4. Click **Upload program**, wait for the program initialization

6. Try sending message to program, check reply:
    1. TBD... 

### Upload program locally from cmd
    
Upload program locally on your node: 

TBD...

# Contribution

You can request a new feature by creating a new Issue or discuss it with us on Discord. 
Here are some features in-prog or planned: https://github.com/gear-tech/gear/issues

# License

Gear is licensed under [GPL v3.0 with a classpath linking exception](LICENSE).

##

<h4>
<table style="align:center; " align="center">
  <tr>
    <td><a href="https://gear-tech.io/">
      <img alt="image" src="https://gear-tech.io/images/footer-logo.svg" height="32">
    </a>
    </td>
    <td><a href="https://wiki.gear-tech.io/">
      Wiki
    </a>
    </td>
    <td>
    <a href="https://gear-tech.io/#community">
      Community
    </a>
    </td>
    <td>
    <a href="https://gear-tech.io/events.html">
      Events
    </a>
    </td>
    <td nowrap>
    <a href="https://gear-tech.io/#about">
      About us
    </a>
    </td>
    <td>
    <a href="https://twitter.com/gear_techs">
        <img src="https://gear-tech.io/images/footer-social-icon-1.svg" alt="twit">
    </a>
    </td>
    <td>
    <a href="https://github.com/gear-tech">
        <img src="https://gear-tech.io/images/footer-social-icon-2.svg" alt="github">
    </a>
    </td>
    <td>
    <a href="https://discord.gg/7BQznC9uD9">
        <img src="https://gear-tech.io/images/footer-social-icon-3.svg" alt="discord">
    </a>
    </td>
    <td>
    <a href="https://medium.com/@gear_techs">
        <img src="https://gear-tech.io/images/footer-social-icon-4.svg" alt="medium">
    </a>
    </td>
  </tr>
</table>
</h4>

<h4>
<p align="center">
<a href="https://gear-tech.io/">
      <img alt="image" src="https://gear-tech.io/images/footer-logo.svg" height="32" style="vertical-align:middle" >
    </a> <a href="https://wiki.gear-tech.io/">
      Wiki
    </a>
    <a href="https://gear-tech.io/#community">
      Community
    </a>
    <a href="https://gear-tech.io/events.html">
      Events
    </a>
    <a href="https://gear-tech.io/#about">
      About us
    </a>
    <a href="https://twitter.com/gear_techs">
        <img src="https://gear-tech.io/images/footer-social-icon-1.svg" alt="twit" style="vertical-align:middle" >
    </a>
    <a href="https://github.com/gear-tech">
        <img src="https://gear-tech.io/images/footer-social-icon-2.svg" alt="github" style="vertical-align:middle" >
    </a>
    <a href="https://discord.gg/7BQznC9uD9">
        <img src="https://gear-tech.io/images/footer-social-icon-3.svg" alt="discord" style="vertical-align:middle" >
    </a>
    <a href="https://medium.com/@gear_techs">
        <img src="https://gear-tech.io/images/footer-social-icon-4.svg" alt="medium" style="vertical-align:middle" >
    </a>
</p>
</h4>