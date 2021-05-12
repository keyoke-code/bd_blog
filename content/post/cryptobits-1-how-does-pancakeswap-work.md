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
This is the first post in our new series on how crypto works. We'll focus on concepts that can really help you lift your crypto investment game, helping you understand crypto a little more and make better decisions. In our first edition we look at pancakeswap. This is something that many people are familiar with, but maybe don't realise what's going on under the covers. 

## What is pancakeswap?

If you're reading this I'm confident that you know what pancakeswap **_does_**. It lets you trade one token for another token. Easy. You know that much already which means you already know quite a lot.

If we take it one step further we find out that pancakeswap is an Automated Market Maker (AMM). It's **automated** because there are no people involved in your trade; pancakeswap is a computer programme running autonomously. It's a **market maker** because it makes the market between the token you want to buy and one you want to sell. Other examples of AMMs include uniswap, 1inch etc. These are different to centralised exchanges (like binance) that are bid / ask market makers,. These market makers have a book of orders with people wanting to sell and others wanting to buy that it tries to match.

Awesome, your crytpo knowledge has levelled up already!

## So how does it work out the price?

I'm glad you asked, because this is the point of today's cryptobits. The pricing on an AMM is remarkably simple! You don't need any complicated maths. It uses something called a **constant product**. 

AMM's use liquidity pools for trades. In each pool there is an equal value of two tokens, called a pair. The **constant product** is calculated as the total number of the first token in the pair multiplied by the number of the second token in the pair. This is best explained with an example, so let's make an imaginary pair between a fictitious token BOB and USDT. The initial load of the liquidity pool sets the relative value of each token. Let's say that we load in 5,000 BOB and 1,000 USDT. 

5,000 BOB = 1,000 USDT (Or in other words, 1 BOB = $0.20)

Our constant product for this pool is therefore 5,000 x 1,000 = 5,000,000

Now, someone comes along and wants to buy some BOB. They want to be a BOB whale, and so want to buy 1,000 BOB. How much will that cost them? Pancakeswap can easily work out the answer. It knows that no matter what happens it needs the constant product to equal 5,000,000. If someone takes out 1, BOB there is only 4,000 left. Our constant product formula therefore looks like this:

4,000 BOB x ? USDT = 5,000,000. OR: 5,000,000 / 4,000 = 1,250 USDT.

So for this trade to work the pool needs 250 more USDT in order for the constant product to be maintained. So we now know that 1,000 BOB will cost 250 USDT. Or, put another way, this trade will value BOB at $0.25. Great, BOB has mooned by 25%!

The pool now has 4,000 BOB and 1,250 USDT. If people keep buying BOB we will need more and more USDT to be traded in their place in order to maintain the constant product. So say we want to buy 250 more BOB. That reduces the number of BOB to 3,750:

3,750 BOB x ? USDT = 5,000,000, OR: 5,000,000 / 3,750 = 1.333.33. 

We had 1,250 USDT in the pool before, so to take out 250 BOB we have to put in 83.30 USDT, so in this trade each BOB costs $0.33. BOB is heading to the moon!

As you can see, as one of the sides of the pairs gets more depleted it's more and more expensive to buy. Scarcity  = value.

## Is that really all there is to it?

Almost. All of the AMMs also charge fees, and there is a liquidity provider reward there to, that does add some complexity, but at the heart of these type of AMMs is this simple arithmetic. Cool huh!

And, of course, there is some complexity around how pancakeswap traverses all the various pairs to mean you can pretty much swap anything for anything, but that's a topic for another day.

## So what?

There's more to this than just idle curiosity. Knowing how prices are derived can really help you pick your investments. For exmaple: are you really impressed with that new token that was loaded with an intial pair valued at $10 that when x100 on the first day? You maybe shouldn't be. . . but that's a topic for our very next 'Staying SAFU', so stay tuned for that!