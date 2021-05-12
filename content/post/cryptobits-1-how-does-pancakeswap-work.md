---
timeToRead: 3
authors: []
title: CryptoBits 1 - How does pancakeswap work?
excerpt: 'The first in a new series: cryptobits. Do you have three minutes to spare?
  Then easily increase your crypto knowledge and power up your investment game!'
date: 2021-05-11T12:00:00+00:00
hero: "/images/cryptobits.png"
draft: true

---
This is the first post in our new series on how crypto works. We'll focus on concepts that can really help you lift your crypto investment game, helping you understand crypto a little more and make better decisions. In our first edition we look at pancakeswap. This is something that many people as familiar with, but maybe don't realise what's going on under the covers. 

## What is pancakeswap?

If you're reading this I'm confident that you know what pancakeswap **_does_**. It lets you trade one token for another token. Easy. You know that much already which means you already know quite a lot.

If we take it one step further we find out that pancakeswap is an Automated Market Maker (AMM). It's **automated** because there are no people involved in your trade, pancakeswap is a computer programme running autonomously. It's a **market maker** because it makes the market between the token you want to buy and one you want to sell. Other examples of AMMs include uniswap, 1inch etc. These are different to centralised exchanges (like binance) that are bid / ask market makers,. These market makers have a book of orders with people wanting to sell and others wanting to buy that it tries to match (bearing in mind that those 'people' may also be robots. . .).

Awesome, your crytpo knowledge has levelled up already!

## So how does it work out the price?

I'm glad you asked, because this is the point of today's cryptobits. The pricing on an AMM like pancakeswap is remarkably simple! You don't need any complicated maths. It uses something called a **constant product**. 

AMM's use liquidity pools for trades. In each pool there is an equal value of two tokens, called a pair. The **constant product** is calculated as the total number of the first token in the pair mutiplied by the number of second tokens in the pair. This easier with an example, so let's make an imaginary pair between our tokens APPLE and PEAR. The initial load of the liquidity pool sets the relative value of each token. I prefer apples, so let's say that 1,000 APPLE is the same value as 5,000 PEAR. We achieve this valuation by loading the liquidity pool with 1,000 APPLE and 5,000 PEAR.

1,000 APPLE = 5,000 PEAR

Our constant product for this pool is therefore 1,000 x 5,000 = 5,000,000