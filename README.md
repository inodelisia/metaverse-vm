# Hyperspace - MainNet Node

[![Discord](https://img.shields.io/discord/586902457053872148.svg)](https://discord.gg/qKMMzcx8)
## Build

### Prerequisites

First let's clone this git repository:
```bash
git clone https://github.com/mvs-org/betelgeuse
cd betelgeuse
```
Install Rust Developer Environment and all required tools:
```bash
curl https://sh.rustup.rs -sSf | sh
source ~/.cargo/env
```
Install necessary dependencies. On Ubuntu, run the following:
```bash
sudo apt update
sudo apt install -y cmake pkg-config libssl-dev git gcc build-essential clang libclang-dev
```
Install this specific Rust nightly version that is known to be compatible with the version of Substrate we are using:
```bash
rustup install 
```

