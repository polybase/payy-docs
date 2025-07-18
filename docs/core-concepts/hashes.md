---
description: A one-way transformation of data to a compact representation.
---

# Hashes

A hash is a series of random numbers and letters that represents some data. Hashes have certain properties that make them great for use in blockchains:

* They are unique. Even the smallest change to the original data makes a vastly different hash. This makes tracking changes easy. Because one hash can only represent one piece of data, it is _collision resistant_; it's highly unlikely to be represented by the same hash (about 1 in 2^128).
* No matter how large the original data is, the hash will always be the same length.
* Hashes allow _one-way encryption_, which means it's impossible to reconstruct the original data from the hash representing it.

<figure><img src="../.gitbook/assets/Frame 2.png" alt=""><figcaption><p>An image and its hash</p></figcaption></figure>

Hashes are crucial in things like securing passwords and maintaining the integrity of blockchain transactions. For [Broken link](broken-reference "mention"), hashes are the representation of transactions that have been validated on our network.
