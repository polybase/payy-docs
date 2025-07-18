---
description: Prove you know something, without revealing anything about it.
---

# Zero Knowledge Proofs

Let's say you're looking at a Where's Waldo book. I see that you're stuck on one of the pages, and I tell you that I can show you where Waldo is. You don't believe that I can, but you also don't want me to give away the puzzle. How do I show you that I know without giving away additional information and ruining the game?

The way I do it is this: I take a large piece of opaque paper, cut a small circle in it, and hold it over the book. In this way, you see that I do, in fact, know where Waldo is. However, you can't see where Waldo is _in the context of the puzzle_, so when I remove the paper, you still don't know where he is.

<figure><img src="../.gitbook/assets/Frame 1.png" alt=""><figcaption><p>Where's Waldo "ZK proof"</p></figcaption></figure>

This is a rough example of a **zero knowledge proof**. In the digital world, zero-knowledge proofs allow for the verification of a statement without revealing any additional information. This concept is particularly powerful in the field of cryptography and has applications in secure voting systems, authentication systems, and blockchain technologies where privacy is paramount.

For [Broken link](broken-reference "mention") specifically, we leverage zero knowledge proofs to maintain full privacy for each transaction. We can verify that the transaction is valid (i.e. you aren't spending more than you have) and that neither transactor has interacted with bad actors on the network.
