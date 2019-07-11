# Spacemesh Local Testnet (Localnet)

Follow this guide to build from source code and run a local Spacemesh Testent (localent) with 6 full nodes, 5 user accounts, and 1 POET support service on your computer using docker. This is a great way to get a feel for the protocol and the platform and to start hacking on Spacemesh.

?> This guide is for developers who are comfortable with the command line, Docker and dev tool chains.

## Prerequisites and Running
👉 `OS X` or a `Linux` system. Windows support is not fully tested yet.
👉 Follow the instructions in the local testnet repo [readme file](https://github.com/spacemeshos/local-testnet) to install the prerequisites and to build and run the testnet.

If all works as expected, you should have a terminal window showing output similar to this:

![](/images/localnet_started.jpg)

?> Got stuck in setup? Got any questions? Join our [Gitter dev channel](https://gitter.im/spacemesh-os/Lobby) and get help.

## Working with the testnet

### Running the CLI Wallet
👉 Now when you have a local testnet is running on your computer - it is time to execute some transactions! Follow these instructions to execute transactions and check balances.

1. Navigate to CLIWallet directory in your go src directory.
```bash
cd $GOPATH/go/src/github.com/spacemeshos/CLIWallet
```
2. Run the wallet:
```bash
./CLIWallet
```

You should see something similar to this:

![](/images/localnet_cliwallet.jpg)

### Viewing account balances

TBR

### Executing a transaction

TBR

### Viewing updated account balances

TBR

### Connecting the wallet to a different node

TBR

### Exploring config files

TBR

### Looking at node logs

👉  You can see each node log output by...

### Stopping the Testnet
👉  Just hit `ctrl-c` in the terminal window you started the Testnet on

----

?> Got stuck? Got any questions? Join our [Gitter dev channel](https://gitter.im/spacemesh-os/Lobby) and get help.
