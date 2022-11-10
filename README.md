# just-simple-dex
Just Simple DEX for Learning Solana + Anchor Smart Contract

## Prerequisite

### Installing Dependencies
To get started, make sure to setup all the prerequisite tools on your local machine (an installer has not yet been developed).

#### Install Rust
For an introduction to Rust, see the excellent Rust book

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source $HOME/.cargo/env
rustup component add rustfmt
```

#### Install Solana
See the solana docs (opens new window)for installation instructions. On macOS and Linux,
```
sh -c "$(curl -sSfL https://release.solana.com/v1.7.11/install)"
```

#### Install Mocha
Program integration tests are run using Mocha (opens new window).
```
npm install -g mocha
```

#### Install Anchor
##### Install using pre-build binary on x86_64 Linux
Anchor binaries are avalable via an NPM package @project-serum/anchor-cli (opens new window). Only x86_64 Linux is supported currently, you must build from source for other OS'.
```
npm i -g @project-serum/anchor-cli
```

## Get started

### Start local test net
```
solana-test-validator
```

### Run test
```
anchor test
```

### Run build
```
anchor build
```

### Run deploy
```
anchor deploy
```
