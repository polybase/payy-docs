---
description: Privacy is a fundamental human right — and it's a non-negotiable for payments.
---

# Privacy

## Introduction

Today, all payments on blockchains like Bitcoin, Solana and Ethereum are publicly visible forever. You can see exactly how much money Vitalk Buterin (Ethereum creator) has, what apps he's interacted with and where he has invested his money: [https://intel.arkm.com/explorer/entity/vitalik-buterin](https://intel.arkm.com/explorer/entity/vitalik-buterin)

This completely breaks a core assumption of money: it should be private.

Stablecoins cannot scale without privacy — this is exactly what Payy unlocks in a scalable, user-friendly way.

Adding privacy to stablecoin payments unlocks trillions of dollars in use cases like payroll, contractor payments, royalty payments and trade finance.

## How privacy works in Payy

When you send a Payy Link or QR, those funds are transfered from your wallet to a new ephemeral wallet which is then embedded in the link. When someone claims the link, those funds are transferred out from the ephemeral wallet to their Payy wallet.

During both of these ([UTXO](../payy-network/05_utxo.md)) transactions, the actual payment data NEVER leaves your device. It is cryptographically impossible for someone to watch the network and try to infer how much money you sent to someone and who you sent it to. Even your Payy Address is never exposed.

This happens because the only data that leaves your device is an updated state hash and a zk proof. More technical details are in our [whitepaper.md](../payy-network/whitepaper.md "mention").

## Enabling compliance

In [06\_compliance.md](../payy-network/06_compliance.md "mention")we discuss various approaches to enabling compliant privacy on Payy Network. This is different from products and protocols pushing for absolute privacy like Zcash, Monero and Tornado Cash. We aim to keep the design space open so we can adapt to changing technology and regulation.

The solution we’ve chosen for now is called UTXO lineage. For a given UTXO note, all of its past parent notes can be traced. However, the transaction amount, sending address and receiving address are still never revealed publicly. This is a unique capability that a UTXO based model has that an account based model like Ethereum cannot enable.
