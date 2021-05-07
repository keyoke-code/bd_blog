---
timeToRead: 3
authors: []
title: 'Staying SAFU #2'
excerpt: 'What is locked liquidity? '
date: 2021-05-05T12:00:00+00:00
hero: "/images/safu-2.png"

---
In today's 'Staying SAFU' we are talking about liquidity locking! Having liquidity locked with a new token is **more** than important, it's **VITAL**! But what is locked liquidity? In fact, what's liquidity? Let's dive in and find out!

## What is liquidity?

When you own an asset (for example a token on BSC, or a car, or even a diamond), it only has value if you can sell it for something. A diamond and a lump of coal are worth exactly the same thing if there is no way of selling them, and that amount is precisely $0. This is liquidity - the formation of an asset pool that means you can trade your asset for the other asset that is in the pool. This pool is often referred to as a pair, in that there is a pair of assets in the pool. You can put one asset back in the pool and receive an equal value of the other asset in exchange.

For crypto this means pairing a new token with something, in BSC this is usually either BNB or BUSD. In ethereum this tends to be with eth. These pools live on the decentralised exchanges (DEXs) like pancakewap.

So to recap, a liquidity pool means you can swap your new token (let's say BitDiamond) for another token (BUSD for example). It's the liquidity pool that means new holders can keep buying BitDiamond, and those who want to hold other tokens can swap to BUSD. Note that DEXs are clever, and can swap across a whole sequence of pairs, meaning you can actually swap one token for almost any other token on pancakeswap. If you do this you can look at your transaction on BSCScan and see all the steps it went to in order to go from the token you are selling to the token you want.

## Sounds awesome, what's the problem?

There is something of a problem with liquidity pools. You create (and add to) a pool by providing equal values of the two tokens in the pair. As the dev team made the token they are the first ones to load liquidity. Hopefully they have loaded most of the tokens in (greater than 95%, more on that in another 'staying SAFU'). When you add liquidity you receive LP tokens that gives you the right to take your tokens out of the pool whenever you want.

And that's the problem. At that point there is nothing to stop a liquidity holder just draining the pool. As we said at the beginning, if there is no liquidity in the pool you can't trade your asset anymore, and whether it is a diamond or a lump of coal it is now almost worthless.

**_This is just one of the types of rugpull that plague low MCAP crypto. The dev team drain the pool and walk off with the cash_**. But there is an answer, and that's called locked liquidity.

## Great. So what is locked liquidity?

It's fairly simple - a third party service provider has a smart contract that allows the staking of an asset with a timelock feature. In other words, you can put an asset (in this case the LP tokens) and set a clock on when that asset becomes free. It cannot be withdrawn before that time. Because that LP token is locked up the liquidity can't be drained.

The important features here are that the locking provider has to be reputable. This means they will be good custodians on the LP tokens and also that they have a well constructed smart contract, free of issues.

There are a number of liquidity locking providers out there. One of the oldest and most reputable is unicrypt. At the time of writing they have a staggering $479M of assets locked. We chose unicrypt as the liquidity locker for BitDiamond - our holders deserve nothing but the very best.

We chose three separate locks for BitDiamond's liquidity:

* 50% for year
* 25% for three months
* 25% for a month

50% for a year let's you know we are around for the long-haul. At the same time it is important to plan for a distribution of liquidity to centralised exchanges (e.g. whitebit, kucoin, binance) in the future. If you lock up all the tokens forever then these exchanges are no longer really an option. Our locking schedule matches our exchange approach - we are aiming for an entry exchange around 1 month from launch, and a tier two exchange after around three months. That at least is the plan.

## So should I check for locked liquidity?

Yes, yes and **yes** again! Thinking about a new token? If it's liquidity is not locked then I suggest you don't buy (not financial advice). This comes down to one of the tenets of crypto: don't trust, _verify_. The team is saying they won't rugpull? You don't need to trust that, but you should verify that they **can't** rugpull by doing a liquidity swipe.

So how do you do this? Quality projects put this front a centre and provide you with a link to the locked liquidity (like on the btdmd.com website). If not, ask for the proof of locked liquidity. And then follow that link and check that most (a percentage in the high 90s) is locked up. Also check for **how long**. I would say you want half to be locked up for a year. Some liquidity unlocking earlier is fine (for example to match an exchange strategy). But liquidity locked for only a month or two would be a red flag for me.

At the same time check out the credentials of the liquidity locking service. This will change as more providers join the industry, but a quick search around telegram should give you some idea of which providers are high quality.

So, in summary, our advice would be to only buy a new token if it has liquidity locked, and locked with a reputable provider for a good amount of time. And because that's what we would need to buy a new token that's exactly what we have done with BitDiamond.

Until next time, Stay SAFU.