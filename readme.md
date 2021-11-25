# Gitcoin Hackathon Training

## Introduction

1. [Introduction](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/introduction/introduction.md)

## Task Setup and Requirements

1. [Task Setup and Requirements](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/task-setup-and-requirements/task-setup-and-requirements.md)

## Gitcoin Tasks

0. [Setup a Local CKB Node and CKB Indexer for the Testnet](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/tasks/0.setup.node.and.indexer.md)

#### 1.A screenshot of the console output from your local Testnet CKB Node after it has fully synchronized with the network.

![task-0_1.png](./img/task-0_1.png)
#### 2.A screenshot of the console output from your local CKB Indexer after it has fully synchronized with the local Testnet CKB Node.

![task-0_2.png](./img/task-0_2.png)

1. [Create a Godwoken Account on the EVM Layer 2 Testnet](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/tasks/1.create.godwoken.account.md)

#### 1.A screenshot of the accounts you created (account list) in ckb-cli.

![task-1_1.png](./img/task-1_1.png)

#### 2.A link to the Layer 1 address you funded on the Testnet Explorer.

https://explorer.nervos.org/aggron/address/ckt1qyq27uneyj39gmsuuft2u5cymn95vvtyh5wqjus9h0

#### 3.A screenshot of the console output immediately after you have successfully submitted a deposit to Layer 2.

![task-1_2.png](./img/task-1_2.png)

2. [Deploy a Simple Ethereum Smart Contract on Polyjuice](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/tasks/2.deploy.eth.contract.md)
3. [Issue a Smart Contract Call to the Deployed Smart Contract](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/tasks/3.issue.contract.call.md)
4. [Issue an SUDT Token on Layer 1 and Deposit it to Layer 2](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/tasks/4.issue.sudt.deposit.md)
5. [Deploy the ERC20 Proxy Contract for the Deposited SUDT](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/tasks/5.deploy.erc20.proxy.contract.md)
6. [Use Force Bridge to Deposit Tokens on Ethereum to Polyjuice](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/tasks/6.use.force.bridge.to.deposit.md)
7. [Port an Existing Ethereum dApp to Polyjuice](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/tasks/7.port.eth.dapp.md)
8. [Modify the Ported dApp so it Supports Ethereum Assets via Force Bridge](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/tasks/8.modify.dapp.support.force.bridge.md)
9. [Initiate a Withdrawal From Layer 2 Back to Layer 1](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/tasks/9.withdraw.md)
10. [Complete Withdrawal Process by Unlocking the Funds](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/tasks/10.unlock.md)
11. [Use a Tron Wallet to Execute a Smart Contract Call](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/tasks/11.tron.call.md)

## Gitcoin Links

1. [Broaden the Spectrum](https://gitcoin.co/hackathon/nervos/onboard)
2. [Bounties List](https://gitcoin.co/hackathon/nervos/)

<!--

## Component Tutorials

1. [Setup a Nervos CKB Layer 1 Account with CKBytes](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/component-tutorials/1.setup.account.in.ckb.cli.md)
2. [Mint SUDT Using Command-Line Tool](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/component-tutorials/2.issue.sudt.cli.md)
3. [Setup and use `account-cli` tool](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/component-tutorials/3.setup.and.use.account.cli.md)
4. [Create a Godwoken Account by Making a Layer 2 Deposit](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/component-tutorials/4.layer2.deposit.md)
5. [Extracting a Private Key from MetaMask Wallet](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/component-tutorials/5.extract.ethereum.private.key.md)
6. ~~[Setup and sync CKB testnet node, indexer and install `ckb-cli`](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/component-tutorials/6.setup.testnet.node.md)~~
7. ~~[Receive an SUDT in Neuron wallet](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/component-tutorials/7.receive.sudt.in.neuron.md)~~

## Conceptual Explainers

- Wallets
	1. [MetaMask](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/conceptual-explainers/wallets.md#metamask)
	2. ~~[Neuron Wallet](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/conceptual-explainers/wallets.md#neuron-wallet)~~
	3. ~~[Portal Wallet](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/conceptual-explainers/wallets.md#portal-wallet)~~
- Tooling
	1. [CKB Node](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/conceptual-explainers/tooling.md#ckb-node)
	2. [CKB Indexer](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/conceptual-explainers/tooling.md#ckb-indexer)
	3. [CKB-CLI](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/conceptual-explainers/tooling.md#ckb-cli)
	4. ~~[Tippy](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/conceptual-explainers/tooling.md#tippy)~~
	5. [CKB.tools](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/conceptual-explainers/tooling.md#ckbtools)
	6. [SUDT-CLI](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/conceptual-explainers/tooling.md#sudt-cli)
- Frameworks
	1. [Godwoken](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/conceptual-explainers/frameworks.md#godwoken)
	2. ~~[Godwoken Kicker](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/conceptual-explainers/frameworks.md#godwoken-kicker)~~
	3. [Polyjuice](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/conceptual-explainers/frameworks.md#polyjuice)
- Infrastructure
	1. [Force Bridge](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/conceptual-explainers/infrastructure.md#force-bridge)
	2. [Nervos Explorer](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/conceptual-explainers/infrastructure.md#nervos-explorer)
	3. [Nervos Faucet](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/conceptual-explainers/infrastructure.md#nervos-faucet)
- Standards
	1. [SUDT](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/conceptual-explainers/standards.md#sudt)
	2. [ERC20](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/conceptual-explainers/standards.md#erc20)
	3. [ERC20 Proxy Contract](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/conceptual-explainers/standards.md#erc20-proxy-contract)
- Structure
	1. [Mainnet/Testnet/Devnet](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/conceptual-explainers/structure.md#mainnet--testnet--devnet)
	2. [Layer 1/Layer 2](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/conceptual-explainers/structure.md#layer-1--layer-2)
	3. [Common User Action Flow](https://github.com/Kuzirashi/gw-gitcoin-instruction/blob/master/src/conceptual-explainers/structure.md#common-user-action-flow)

-->
