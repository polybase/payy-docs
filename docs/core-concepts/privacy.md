---
description: Our goal is to provide the most privacy for the greatest number of people.
---

# Privacy

In [06\_compliance.md](../payy-network/06_compliance.md "mention")we discuss various approaches to enabling compliant privacy on Payy Network. We aim to keep the design space open so we can adapt to changing technology and laws.

The solution we’ve chosen for now is called UTXO lineage. For a given UTXO note, all of its past parent notes can be traced. However, the transaction amount, sending address and receiving address are still never revealed publicly. This is a unique capability that a UTXO based model has that an account based model like Ethereum cannot enable.

## How privacy works in Payy

When you send a Payy Link or QR, those funds are transfered from your wallet to a new ephemeral wallet which is then embedded in the link. When someone claims the link, those funds are transferred out from the ephemeral wallet to their Payy wallet.

During both of these ([UTXO](../payy-network/05_utxo.md)) transactions, the actual payment data NEVER leaves your device. It is cryptographically impossible for someone to watch the network and try to infer how much money you sent to someone and who you sent it to. Even your Payy Address is never exposed.

This happens because the only data that leaves your device is an updated state hash and a zk proof.
