---
description: How private key backup works in Payy Wallet
---

# Key backup

Since [payy-wallet.md](../product/payy-wallet.md "mention") is a non-custodial wallet, a private cryptographic key is used to secure your balance and transactions. This key is only controlled by you and is used by Payy Wallet to execute transactions on your behalf (when you send/receive/deposit/widthdraw).

The first time you open the wallet, a new key will be generated and backed up using either iCloud (on iPhones) or Android backup. If you don't have either of those backup systems enabled, your private key is not backed up and you could lose your funds if you lose your phone.

You can always manually backup your key by exporting your seed phrase in Advanced Settings. This seed phrase can be used to restore your wallet on a new device.

Your wallet data is encrypted by your key and the end-to-end encrypted backup is stored in our database so you can recover your wallet if you get a new phone and restore your iOS or Android backup.

Many aspects of this backup system are in development, with the goal of making it extremely difficult or impossible to lose your keys.
