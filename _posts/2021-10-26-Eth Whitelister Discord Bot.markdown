---
layout: post
title:  "Ethereum Whitelister Discord Bot"
date:   2021-10-26 12:13:58 +0000
categories: crypto discord
---

This <strong>Discord</strong> bot allows members of your Discord server to whitelist one <strong>Ethereum</strong> address per account using slash commands. You can set a specific deadline, after which whitelists will be closed, or you can manually open/close whitelisting. Members can whitelist as many times as they want, but each time will override the existing address. It will resolve <strong>ENS</strong> domains too. The whitelist can then be exported as a JSON containing Discord user ID to Ethereum address mappings.

An easy installation script is provided that will ask you to input the required configuration parameters and will then install as a <strong>Linux</strong> service. You can check out the code or install it [here](https://github.com/Sploot-NFT/eth-whitelister-bot).
