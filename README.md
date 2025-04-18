# Solana Setup + Deployment
## Description
The project is aimed at exploring and practicing Solana smart contract development using Rust and the Solana CLI. The project is the implementation of the Blockchain Technologies II Assignment 2.2 task.

## Used technologies:
- Rust
- Solana CLI

## Build
### Use this command to build
<pre> cargo build-sbf </pre>

## Deploy
### Use this commands to deploy:
### First, configure the Solana CLI to use the local Solana cluster.
<pre> solana config set -ul </pre>

![screenshot2](https://github.com/user-attachments/assets/de3d8cfe-e049-42f6-9da3-c59ae9d47362)

### Then deploy.
<pre> solana program deploy ./target/deploy/untitled19.so </pre>

![screenshot3](https://github.com/user-attachments/assets/0f12b8e4-d262-4308-b096-aea8331ebebf)

### Check the address.
<pre> solana address </pre>

![screenshot](https://github.com/user-attachments/assets/b1e71868-0b00-4e01-aa87-61133432f79f)

## Team members:
- Temirlan Turgimbayev, SE-2321
- Amirkhan Turgimbayev, SE-2322
- Abdykhalykk Dias, SE-2322

