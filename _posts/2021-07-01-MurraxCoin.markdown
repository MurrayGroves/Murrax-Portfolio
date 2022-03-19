---
layout: post
title:  "MurraxCoin"
date:   2021-07-01 12:13:58 +0000
categories: murraxcoin crypto
---

This project was my first foray into Web3 development. I figured that instead of starting small and building something with an existing crypto, I'd just make my own. Because why not. You can check out the code and get your own <strong>$MXC</strong> for free [here](https://github.com/MurrayGroves/MurraxCoin#Tutorial).

It's purely educational so doesn't actually have a use. I decided to make it in Python because at the time I didn't know any other languages, and I would rather learn a new concept in a familiar language. Obviously this isn't an ideal language choice for a real cryptocurrency with actual performance demands, but this network is hardly going to be handling many transactions.

As a consensus mechanism I decided to use my own implementation of Open Representative Voting which is what [Nano](https://docs.nano.org/protocol-design/orv-consensus/) uses. I chose this because I don't like Proof of Work, and it's simpler than Proof of Stake.

Another mechanism of Nano I used/stole is using a [block lattice](https://medium.com/nano-education/nano-how-2-blocks-and-lattices-c0ccd417bd5a) instead of a traditional blockchain. The benefits of this are multitude; it's easier to understand, scales better (not really relevant here though) and perhaps most importantly - it's easier to rollback when I inevitably make mistakes. In a traditional blockchain, rollbacks have to remove all blocks after the transaction you want to remove. In a block lattice however, only transactions directly involved or referencing those directly involved have to be removed.

I learned a lot from this project, especially from the whitepapers I read. <strong>MurraxCoin</strong> is still used within my sixth form community, which is pretty cool.
