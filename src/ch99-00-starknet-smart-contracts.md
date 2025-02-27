# Starknet Smart Contracts

All through the previous sections, you've mostly written programs with a `main` entrypoint. In the coming sections, you will learn to write and deploy Starknet contracts.

Starknet contracts, in simple words, are programs that can run on the Starknet VM. Since they run on the VM, they have access to Starknet’s persistent state, can alter or modify variables in Starknet’s states, communicate with other contracts, and interact seamlessly with the underlying L1.

Starknet contracts are denoted by the `#[contract]` attribute. We'll dive deeper into this in the next sections.
If you want to learn more about the Starknet network itself, its architecture and the tooling available, you should read the [Starknet Book](https://book.starknet.io/). This section will focus on writing smart contracts in Cairo.

#### Scarb

You can set up a Starknet development environment using Scarb as stated in the [Hello, Scarb! - Starknet Support](ch01-03-hello-scarb.md#starknet-support) section. Each example in this chapter can be used with Scarb.
