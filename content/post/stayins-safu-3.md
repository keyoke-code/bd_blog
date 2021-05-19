---
timeToRead: 5
authors: []
title: 'Stayins SAFU #3'
excerpt: Wow, that token just went 10x!? But does that look like good liquidity?
date: 2021-04-19T12:00:00+00:00
hero: "/images/safu-2.png"
draft: true

---
In today's 'Staying SAFU' we're going to dive a little bit more into liquidity. (Get it, _dive_ in. To **liquidity** :p).

There's three things I want to cover off in this issue, the first one is particularly topical given recent market events.

1) Looking at the main liquidity pair for a token and deciding how that fits with your risk profile. 

2) Checking out the value of the initial liquidity load, and understanding what that means for price dymanics.

3) Considering looking at the mcap to liquidity ratio.

## The main liquidity pair. Does it matter?

We think it does. What a lot of people don't realise is that when you buy a token you are taking a long position in both that token AND it's liquidity pairs. 

Now, I am sure there are crypto maximalists out there who never think in $ terms. They view their wealth as how many BTC, or ETH, or BNB they have. But for most of us we still think in fiat currency terms. We want to see what our holding is worth in something like USD. Hence that's what the charts show. Now, lets say your token has one liquidity pair on pancakeswap and the other token in that pair is BNB. What that pool says is that a certain amount of your new token can be swapped for a certain amount of BNB. Not $, BNB. Lets say you have 1,000 tokens and they are worth 1 BNB.

So what happens if the price of BNB changes? Let's say no one buys the token you hold, no one sells it, but BNB tanks by 45%. Your token can still be traded in the pool for 1 BNB. That hasn't changed. But if 1 BNB was worth $650 before the drop, and is now worth $360. The tokens that you hold now have a $ value of $360. In $ terms you are down 45%, just like BNB.

To reiterate the point at the start of this section, when you buy a token you are taking a long position in that token and also it's pair. This is particularly important if there are not many pairs, even more so if there is just one pair available.

With this in mind we loaded 97% of BitDiamond in a pair with a **stablecoin**, BUSD. Our $ price hasn't been affected by the recent pullbacks across the market, as our pair is still pegged to the $. That's not to say we haven't seen volatility, but at least we know the underlying basis for our token isn't shifting beneath our feet.

So how do you check this information? Go to [https://bscscan.com/](https://bscscan.com/ "https://bscscan.com/") and enter your token contract hash. Always use that, not the name, there are almost always clones of any token. You should be able to get the address from the dev team. They should have a website, or a telegram group, with all this information front and centre.

Once you are here, click on the 'Holders' list and look for the pancakeswap pool or pools. These will have little contract icons. Click on one of these, and in the next screen click on the address under 'Filtered by Token Holder' (about half way down the right hand side). You are now viewing what the liquidity pool holds. Cool, right!? Click on the little square shaped icon next to the drop down that says 'Token' (third item on the left hand side).

You can now see what tokens are in the pool! So what is your token paired with? Are you happy going long on this?

## Initial Liquidity Load. Why should I care?

You should care because it can tell you a number of things, and help you to evaluate what's happened to the token since launch. This is a little but more involved than some of our other tips, but it's worth learning. Here's what to look for.

Check on BSCScan