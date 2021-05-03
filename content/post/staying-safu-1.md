---
timeToRead: 3
authors: []
title: 'Staying SAFU #1'
excerpt: Looking at contract auto-scanners
date: 2021-05-03T12:00:00+00:00
hero: "/images/safu-2.png"

---
This is the first post in our 'Staying SAFU' series. In this series we will be looking at all the ways you can increase the safety of your crypto purchases. We will be focussing on ERC20 and BEP20 tokens (so tokens on Ethereum and Binance Smart Chain). We'll cover what steps you can take before making a token purchase to decrease your chances of being scammed.

## Contract autoscanners

First up we are going to look at contract auto-scanners. These services aim to do an automatic assessment of a contract's solidity source code and tell you whether there is anything in there to be worried about. An example is [https://rugscreen.com/](https://rugscreen.com/ "https://rugscreen.com/") . The idea is that you paste in the source code and the scanner tells you whether this is a rug or not.

So, do these services work? We've had a lot of discussion on the team. We like to see new developments that aim to make crypto safer. But, in this instance, we think **these services as they currently are make crypto a lot more dangerous**. They claim to give an idea of whether a contract is a rug or not, but the reality is they miss most rugs, and incorrectly label legitimate tokens as scams. Most rugs have nothing to do with the smart contract at all. In later editions of this series we'll cover off what happens in most rugs, and it isn't a smart contract exploit. And at the moment these scanners are flagging code statements as 'risky' that are not at all. The result is that people miss out on good projects and still wander into the hands of the scammers.

Our "staying SAFU" verdict: Does not make crypto safer, on balance if anything makes it more dangerous, as people feel they can rely on it's verdict. And you can't!

## Putting it to the test - the rugs

So lets put one of these scanners to the test and see how useful it is. We'll take [https://rugscreen.com/](https://rugscreen.com/ "https://rugscreen.com/") as an example. Let's see how well rugscreen would have protected us from the last five confirmed token rugpulls as reported by certic:

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

![](/images/ghostmixer.png)

Didn't catch this rugpull either.

### Rugpull scan results

So, of the five most recent token rugpulls [https://rugscreen.com/](https://rugscreen.com/ "https://rugscreen.com/") said categorically that FOUR of them were 'Not A Rug'. And for the one it detected it didn't even get the reason for the rug right (I mean, it can't know if a team is going to exit scam).

This is a huge worry, and shows why a simple autoscan like this makes crypto more dangerous, not less.

## Putting it to the test - the gems

What about the other side of the equation, the good projects that these scanners label as rugs? Let's look at those.

### Poocoin

Most of us will know poocoin, a recent gem of BSC. Does [https://rugscreen.com/](https://rugscreen.com/ "https://rugscreen.com/") this this is a rugpull?

[https://bscscan.com/address/0xb27adaffb9fea1801459a1a81b17218288c097cc#code](https://bscscan.com/address/0xb27adaffb9fea1801459a1a81b17218288c097cc#code "https://bscscan.com/address/0xb27adaffb9fea1801459a1a81b17218288c097cc#code")

![](/images/poocoin.png)

Yup. It's so certain, it's 'definitely' a rug. OMG.

### BitDiamond

And yes, what about our own token. What does the scanner say?

[https://bscscan.com/address/0x669288ada63ed65eb3770f1c9eeb8956dedaaa47#code](https://bscscan.com/address/0x669288ada63ed65eb3770f1c9eeb8956dedaaa47#code "https://bscscan.com/address/0x669288ada63ed65eb3770f1c9eeb8956dedaaa47#code")

![](/images/bitdiamond.png)

It reckons it is.

So what is the scanner looking at here? It's worryingly oversimplfied. It has a problem with this function in both poocoin and BitDiamond:

![](/images/codeblock.JPG)

This is the anti-whale feature that limits each transaction to 1% of supply. This stops snipe bots getting a huge share on launch, and also limits a whale's ability to pump and dump. It's a good innovation. BUT, it has to exclude the contract owner (which means it needs to compare to a non-zero address).

Why? Because otherwise it would take 100 transactions to load all the tokens into liquidity (100 x 1%) which would take ages and cost a lot of gas. Also when new exchanges are added (whitebit, kucoin, binance etc), they need a supply of tokens. That's likely to be more than 1% of supply, so the contract owner needs to be able to send more than 1% to those exchanges on launch.

Does this feature make it a rug? Not even slightly.

## Conclusion

Be very very careful of autoscanners. They will tell you that future rugs are safe, and future gems are rugs. **They are, to put it politely, totally useless services, as well as being dangerous in their claims to detect rugs.**

What should you do instead? Only buy tokens that have been audited by a REPUTABLE smart contract auditor. They wouldn't let a simple smart contract exploit through, and they have the experience to read features like the above and realise they add safety rather than take it away.

We'll publish another article on how to interpret contract audits (hint - BitDiamond has one already from one of the best auditors in the business, Quillhash).

In the meantime, stay SAFU.