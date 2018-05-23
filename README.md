Design Of Basechain
===
Basechain is a project which aims at building blockchain and distributed system easily and rapidily. 
This repository contains documents describing the design and high-level overview of Basechain.

Basechain provides three tools:

- Basechain Network: Basechain Network is a blockchain and network. And you can deploy a smart contract or a chain contract here. A chain contract is a model file which contains how a new blockchain works. Anyone want to run it could start service and be rewarded according to the the chain contract.

- Base Framework: Base is a framework which helps you build blockchain. It parameterize and modularize the architecture of blockhain. 

- Gap Test Suite: Gap is a test enviroment for you to quickly verify your idea on distributed system. And it could help simulate processing data of your distributed system to tell you how your nodes changes.

### Guides

In the final goal, you can build and deploy your blockchain like the followings:

block(blk) is a tools of baseframework like node and bpm is blk package manager:

```
bpm init

```

And you will fill into basic information

- chainName
- version
- description
- author

Then It will create four folders in you project root directory.

```
.
├── chain.json
├── application
├── consensus
├── negotiate
└── node
```

![Architecture](Architecture.png)
