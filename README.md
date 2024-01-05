# Documentation <!-- omit in toc -->

- [Windows](#windows)
  - [File explanation](#file-explanation)
  - [Basic configuration](#basic-configuration)

# Windows

Simply download this repository and run the `Nukra Wallet.exe` file. If you get a warning from Windows Defender, click on `More info` and then `Run anyway`.

When you run the wallet for the first time it will ask you if you want to change the installation directory, we recommend that you do not do this and leave the option checked by default, Nukra Wallet will be installed to `%APPDATA%/Nukra` (C:\Users\YourName\AppData\Roaming\Nukra)

## File explanation

- `Nukra Wallet.exe`: The executable wallet file.
- `nukra-cli.exe`: The command line interface for the wallet.
- `nukrad.exe`: The Nukra daemon, use for run a node without pool mining.
- `nukra-tx.exe`: The Nukra line interface for transactions.

## Basic configuration

When you open the wallet, in the top tabs, click on `Settings` and then on `Options...`.

In the window that has opened, click on `Open configuration file` and paste the following:

```conf
rpcuser=rpc_nukra
rpcpassword=dR2oBQ3K1zYMZQtJFZeAerhWxaJ5Lqeq9J2
rpcbind=127.0.0.1
rpcallowip=127.0.0.1
listen=1
server=1
maxtxfee=1.0
addnode=node1.nukra.io
```
