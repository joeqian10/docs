# Setting up local network

## Setting up a private chain

Neo provides a test net for development, debugging and testing purposes. Besides, you can also choose to set up your own private chain where you can get more flexibly with plenty of test tokens. You can pick one of the following options:

- [Set up a private chain using virtual machines](../../network/private-chain/private-chain.md)
- [Set up a private chain on a Windows host](../../network/private-chain/private-chain2.md)
- [Set up a private chain with one node](../../network/private-chain/solo.md) (Applicable to Neo-CLI 2.10.2 and the later)

Refer to the instructions from above links to set up your private chain and withdraw NEO and GAS from genesis block.

> [!Note]
>
> Since GAS is generated along with every new generated block, it is recommended that you keep the new-built private chain running a while to generate enough GAS. Smart contract deployment and invocation will cost a certain amount of GAS.

## Preparing a wallet file

Now let's create a new wallet file used for deploying smart contracts.

1. Create a new wallet file named 0.json and copy the default address for later usage.
2. Open the wallet where you have withdrawn NEO and GAS from genesis block, transfer all the assets in that wallet to 0.json and wait for the transaction to be confirmed.
3. Open 0.json and assets is displayed in the account.

## What's next?

[Compiling a contract sample](develop.md)
