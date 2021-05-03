---
timeToRead: 3
authors: []
title: 'Staying SAFU #1'
excerpt: Looking at contract auto-scanners
date: 2021-05-03T12:00:00+00:00
hero: ''
draft: true

---
This is the first post in our 'Staying SAFU' series. In this series we will be looking at all the ways you can increase the safety of your crypto purchases. We will be focussing on ERC20 and BEP20 tokens (so tokens on Ethereum and Binance Smart Chain). We'll cover what steps you can take before making a token purchase to decrease your chances of being scammed.

### Contract autoscanners

First up we are going to look at contract auto-scanners. These services aim to do an automatic assessment of a contract's solidity source code and tell you whether there is anything in there to be worried about. An example is [https://rugscreen.com/](https://rugscreen.com/ "https://rugscreen.com/") . The idea is that you paste in the source code and the scanner tells you whether this is a rug or not.

So, do these services work? We've had a lot of discussion on the team. We like to see new developments that aim to make crypto safer. But, in this instance, we think these services as they currently are make crypto a lot more dangerous. They claim to give an idea of whether a contract is a rug or not, but the reality is they miss most rugs, and incorrectly label legitimate tokens as scams. The thing is, most rugs have nothing to do with the smart contract at all. In later editions of this series we'll cover off what happens in most rugs, and it isn't a smart contract exploit. And at the moment these scanners are flagging code statements as 'risky' that are not at all. The result is that people miss out on good projects and still wander into the hands of the scammers.

Our staying SAF verdict: <span class="iconify" data-icon="ic:baseline-dangerous" data-inline="false"></span> Does not make crypto safer, on balance if anything makes it more dangerous, as people feel they can rely on it's verdict.

## Putting it to the test

So lets put one of these scanners to the test and see how useful it is. We'll take [https://rugscreen.com/](https://rugscreen.com/ "https://rugscreen.com/") as an example. Let's see how well rugscreen would have protected us from the last five confirmed rugpulls as reported by certic:

### Spartan Protocol 

[https://bscscan.com/address/0xe4ae305ebe1abe663f261bc00534067c80ad677c#code](https://bscscan.com/address/0xe4ae305ebe1abe663f261bc00534067c80ad677c#code "https://bscscan.com/address/0xe4ae305ebe1abe663f261bc00534067c80ad677c#code")

This was confirmed as a scam by certik on 2 May 2021. 

![](/images/spartan.png)

Oh dear, it missed that one. Not a great start. 0 from 1.

### Moonhere

[https://bscscan.com/address/0xc1468757b6236a19a0c46c4435a5a6e2f4d9c0f3#code](https://bscscan.com/address/0xc1468757b6236a19a0c46c4435a5a6e2f4d9c0f3#code "https://bscscan.com/address/0xc1468757b6236a19a0c46c4435a5a6e2f4d9c0f3#code")

![](/images/moonhere.png)

It got that one. But moonhere was an exit scam according to certik, which means the team exited and took the cash, which you could **never tell was going to happen from the smart contract.**

### SexyAPY

[https://bscscan.com/address/0xda2ace303531079568e471bb5962d9c7892e2619#code](https://bscscan.com/address/0xda2ace303531079568e471bb5962d9c7892e2619#code "https://bscscan.com/address/0xda2ace303531079568e471bb5962d9c7892e2619#code") 

![](/images/sexyapy.png)

Another miss.

### Noaswap

[https://bscscan.com/address/0x8e97c451d4e5b4337e3e03c5b1e900d122f34899#code](https://bscscan.com/address/0x8e97c451d4e5b4337e3e03c5b1e900d122f34899#code "https://bscscan.com/address/0x8e97c451d4e5b4337e3e03c5b1e900d122f34899#code")

![](/images/noaswap.png)

Missed again.

### Ghostmixer

[https://bscscan.com/address/0x68f15dfb746f9453441afc68002dca183833bb17#code](https://bscscan.com/address/0x68f15dfb746f9453441afc68002dca183833bb17#code "https://bscscan.com/address/0x68f15dfb746f9453441afc68002dca183833bb17#code")