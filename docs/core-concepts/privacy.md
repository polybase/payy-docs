---
description: Our goal is to provide the most privacy for the greatest number of people.
---

# Privacy

In [06\_compliance.md](../payy-network/06_compliance.md "mention")we discuss various approaches to compliant privacy. We aim to keep the design space open so we can adapt to changing technology and laws.

The solution we’ve chosen for now is called UTXO lineage. For a given UTXO note, all of its past parent notes can be traced. However, the transaction amount, sending address and receiving address are still never revealed publicly. This is a unique capability that a UTXO based model has that an account based model like Ethereum cannot enable.
