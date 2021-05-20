---
timeToRead: 5
authors: []
title: 'Stayins SAFU #3'
excerpt: Wow, that token just went 10x!? But does that look like good liquidity?
date: 2021-05-19T12:00:00+00:00
hero: "/images/safu-2.png"

---
In today's 'Staying SAFU' we're going to dive a little bit more into liquidity. (Get it, _dive_ in. To **liquidity**.). This is quite a big one. Settle back and ignore the market!

There's FOUR things I want to cover off in this issue, the first one is particularly topical given recent market events.

1) Looking at the main liquidity pair for a token and deciding how that fits with your risk profile. 

2) Checking out the value of the initial liquidity load, and understanding what that means for the price dynamics.

3) Considering looking at the MCAP to liquidity ratio.

4) Checking how much of the total supply is in liquidity.

## The main liquidity pair. Does it matter?

Yes. What a lot of people don't realise is that when you buy a token you are taking a long position in both that token AND it's liquidity pairs. 

Now, I am sure there are crypto maximalists out there who never think in $ terms. They view their wealth as how many BTC, or ETH, or BNB they have. But most of us still think in fiat currency terms. We want to see what our holding is worth in something like USD. Hence that's what the charts show. 

Now, lets say your token has one liquidity pair on pancakeswap and the other token in that pair is BNB. The pool says that a certain amount of your new token can be swapped for a certain amount of BNB. Not $, BNB. Lets say you have 1,000 tokens and they are worth 1 BNB.

So what happens if the price of BNB changes? Let's say no one buys the token you hold, no one sells it, but BNB tanks by 45%. Your token can still be traded in the pool for 1 BNB. That hasn't changed. But 1 BNB was worth $650 before the drop, and is now worth $360. The tokens that you hold now have a $ value of $360. In $ terms you are down 45%, just like BNB.

To reiterate the point at the start of this section, when you buy a token you are taking a long position in that token and also it's pair. This is particularly important if there are not many pairs, even more so if there is just one pair available.

With this in mind we loaded 97% of BitDiamond in a pair with a **stablecoin**, BUSD. Our $ price hasn't been affected by the recent pullbacks across the market, as our pair is still pegged to the $. That's not to say we haven't seen volatility, but at least we know the underlying basis for our token isn't shifting beneath our feet.

So how do you check this information? Go to [https://bscscan.com/](https://bscscan.com/ "https://bscscan.com/") and enter your token contract hash. Always use that, not the name, there are almost always clones of any token. You should be able to get the address from the dev team. They should have a website, or a telegram group, with all this information front and centre.

Once you are here, click on the 'Holders' list and look for the pancakeswap pool or pools. These will have little contract icons. Click on one of these, and in the next screen click on the address under 'Filtered by Token Holder' (about half way down the right hand side). You are now viewing what the liquidity pool holds. Cool, right!? Click on the drop down that says 'Token' (third item on the left hand side).

You can now see what tokens are in the pool! So what is your token paired with? Are you happy going long on this token?

## Initial Liquidity Load. Why should I care?

You should care because it can tell you a number of things, and help you to evaluate what's happened to the token since launch. This is a little but more involved than some of our other tips, but it's worth learning.  

It's important to know the value of the liquidity pool at launch. A lot of tokens are loading very low values of initial liquidity. Why this matters is best expressed with two examples.

Token A and Token B both have a total supply of 100M. To make the math easier let's say they loaded all 100M tokens to the liquidity pool on launch, and they both paired with BUSD. 

Token A paired their tokens with 2,000 BUSD. Token B paired with 40,000 BUSD.

Token A has a starting unit price of 2,000 / 100,000,000. So $0.00002 per token. That's a total diluted MCAP of $2,000. 

Token B has a starting price of 40,000 / 100,000,000. So $0.004 per token. For token B the MCAP is therefore $40,000.

Makes sense so far.

We've built our own AMM model here at BitDiamond so we can model what happens to these imaginary tokens when sales come in. Let's image they both experience 10 buys of $200 each in the first few hours. 

Because token A had a very low initial liquidity value these 10 buys of $200 have doubled the $ value of the liquidity pool to $4,000. And that has had a big % price impact - token A is up 143% on token price and has an MCAP of $7,600. Wow, looks like huge growth! Token B has also had it's liquidity pool grow by $2,000, so it's now $42,000. And it's unit price increase? Just 9.3%. It's MCAP is now $43,890. 

The MCAP of token B has gone up $3,890. The MCAP of token A has gone up by $5,600. Token A looks a LOT more attractive, right?! That isn't the case. What you are seeing is a huge **percentage** impact on a very low starting valuation. This is why you see lots of tokens with tiny initial liquidity values and quadrillions of tokens in total supply. Both token A and B have the same sales, and have gone up the same in liquidity terms. It looks like token A is pumping, but I would say token B is the MUCH better buy.

To illustrate this let's look at what happens when someone SELLS. Let's put the 11th trade for each as a $500 sale.

For token B, with good liquidity, we see a price drop of 0.71%. Not a disaster. For token A the drop is 11.11%! 

The numbers can get confusing, but if you want one take away from this section it's the following. It's possible to setup a token such that it will moon very very easily. It looks great, huge green candle. Much wow. Everyone piles in. But that token can (and indeed probably will) crash hard! This is token A in our example. Token B will grow steadily, and when bad times come it will keep taking punches in the face like a champ, and not drop like a rock! This is why we loaded BitDiamond with $40k of liquidity on day one.

Want to see what the initial liquidity load was? Are you still looking at the liquidity pool in BSCscan from the above section? If not, follow the instructions on how to get here from the section above. Now, click Bep-20 Token Transactions and hit view all. Go to 'last' and look for the liquidity load transaction. Ideally this will be the first thing you see, and you can check out how much it was.

## MCAP to Liquidity Ratio

Want an easier way to see how SAFU the token is going to be in terms of huge price movements? Calculate the MCAP to liquidity ratio. The longer a token has been around this will or course diverge a lot, but it's not a bad number to know.

Remember, liquidity is what's available for token holders to sell in and out of. MCAP is the total supply multiplied by the most recent trade price.

To work out this ratio just take total liquidity and divide by MCAP. Bogged.finance charts are a great place to see this easily (e.g. [https://charts.bogged.finance/?token=0x669288ADA63ed65Eb3770f1c9eeB8956deDAaa47](https://charts.bogged.finance/?token=0x669288ADA63ed65Eb3770f1c9eeB8956deDAaa47 "https://charts.bogged.finance/?token=0x669288ADA63ed65Eb3770f1c9eeB8956deDAaa47")). For BitDiamond this gives us a current ratio of 0.79. For safemoon it's 0.07. Every $ in BitDiamond's MCAP is backed in liquidity terms by over ten times as much $ as safemoon.

Now, these two tokens are in entirely different stages of their lifecycle. But try this ratio on your next low MCAP pick and see what you think.

## Checking the total supply in liquidity

We'll finish on an easy one. How much of the supply was added to liquidity? It HAS to be almost all of it.

Want to setup a token with a $1bn fully diluted MCAP? Do the following:

Create a token with 1bn supply

Pair ONE of those tokens with ONE dollar in the liquidity pool.

The unit price is 1 token = $1. The fully diluted market cap is therefore $1 x 1bn. So $1,000,000,000.

Is this token's total supply worth that? Of course not. If the dev team hasn't loaded almost all the token into liquidity you need to ask why. 

Until next time, stay SAFU!