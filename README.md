# Nexus-Prover

**1. Install Dependecies**
```console
sudo apt update && sudo apt upgrade -y
```
```console
sudo apt install curl iptables build-essential git wget lz4 jq make gcc nano automake autoconf tmux htop nvme-cli pkg-config libssl-dev libleveldb-dev tar clang bsdmainutils ncdu unzip libleveldb-dev  -y
```
```console
sudo curl https://sh.rustup.rs -sSf | sh
```
```console
source $HOME/.cargo/env
export PATH="$HOME/.cargo/bin:$PATH"
```
```console
rustup update

rustc --version
```

**2. Run Prover**

```console
screen -S nexus
```
```console
sudo curl https://cli.nexus.xyz/install.sh | sh
```
To minimize screen: `CTRL+A+D`

To retun screen: `screen -r nexus`



**3. Save Prover ID file**

You'll get a `prover-id` file in `/root/.nexus/` representing your unique contribution ID to Prover Node
