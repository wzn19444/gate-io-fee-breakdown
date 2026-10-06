# gate io trading fees: What You Actually Pay at VIP 0, How GT Drops It to 0.09%, and Where the Discount Stops Working

Search for these fees on a Monday and you'll see 0.1%. Search again on a Thursday and someone's guide says 0.2%. Both numbers are floating around, both look authoritative, and neither comes with a date.

Here's what's actually going on: Gate rebuilt its spot and futures fee schedule on April 9, 2026, and a lot of the content ranking for this keyword was written before that, or copied from something that was. The rate that bills your order is the one on Gate's fee overview page, and the numbers below come from that page and the official announcement that changed it.

## The numbers that matter at VIP 0

If you just signed up and haven't traded anything yet, this is your whole fee sheet:

| What you're doing | Rate |
| --- | --- |
| Spot, limit order that rests on the book (maker) | 0.10% |
| Spot, market order (taker) | 0.10% |
| Spot, same orders with fees paid in GT | 0.09% |
| USDT-margined perpetual futures, maker | 0.020% |
| USDT-margined perpetual futures, taker | 0.050% |
| Alpha (on-chain token venue) | 0.80% flat |
| USDC/USDT pair | 0% maker, 0% taker |
| Crypto deposit | 0 |

Two of those deserve a second look before you do anything else.

The Alpha rate is 0.8% at every single tier, all the way up. It never falls. That's eight times the VIP 0 spot rate, and no amount of volume or GT holdings changes it.

The USDC/USDT pair is free on both sides. It's the cheapest way to move between the two big stablecoins on the platform, and Gate explicitly excludes that pair's volume from VIP tier calculations, so it won't accidentally help you climb.

## Why you keep seeing 0.2% quoted

Gate's own blog has published VIP 0 spot at 0.20% on a page that was still live and dated after the fee change. Third-party comparison sites have repeated it. Meanwhile the fee overview page, which is the schedule that actually deducts from your orders, shows 0.10%.

The practical rule: treat the fee overview page as the billing truth, and treat any rate you read without a retrieval date as an old rate. This isn't academic — on $500,000 of monthly taker volume, 0.1% versus 0.2% is $500 versus $1,000 a month.

## Maker and taker mean nothing at VIP 0

Most fee guides explain maker-versus-taker as if it always matters. On Gate, for your first four tiers it doesn't.

VIP 0 through VIP 3 charge the same rate on both sides. Resting a limit order on the book costs you exactly what crossing the spread costs, so the usual advice to "use limit orders to save on fees" buys you nothing until VIP 4, where the two columns finally split (0.095% maker against 0.096% taker). It's a narrow split at first — under one basis point all the way to VIP 9 — and it only gets wide in the upper tiers.

That's worth knowing if you're choosing an exchange partly on maker rebates. A trader who works limit orders exclusively pays the full VIP 0 bill at Gate. If limit-order flow is your whole strategy, run the arithmetic against platforms that price makers at zero from tier one rather than assuming all exchanges reward liquidity the same way.

👉 [Open a Gate account and see your live rate before you size your first order](https://bit.ly/GateVIP)

## The GT deduction, and the part nobody warns you about

GT is Gate's platform token, and using it to pay spot fees takes VIP 0 from 0.10% to 0.09%. On a $10,000 buy that's $9 instead of $10. On $1,000,000 of monthly turnover, the gap between 0.1% and 0.09% is roughly $100 a month.

Small, but real. The catch is how the deduction behaves.

> Once GT deduction is on, Gate spends your GT balance first. The moment it runs dry, the system silently reverts to your standard VIP rate for the rest of the session.

So if you budgeted a month at 0.09% and your GT balance empties halfway through a trading day, the remaining fills bill at 0.10% and nothing tells you. Either keep the balance topped up or watch it.

There's a second limit worth knowing: from VIP 10 upward, the GT-paid column and the standard VIP column are the same number. Paying in GT stops buying you a discount at exactly the tiers where fees are smallest and volumes are largest. Below VIP 10 it helps; at VIP 10 and above it's decorative.

## Gate's full fee tiers, VIP 0 to VIP 16

Every tier on the current schedule. The price here is the rate per trade — Gate charges no account fee, no subscription, and no monthly minimum. Your tier is assessed against your own 30-day volume, your 14-day average GT holding, or your qualifying account asset value, and the best of the three wins.

| Tier | 30-day volume (USD) | VIP maker / taker | GT maker / taker | Open an account |
| --- | --- | --- | --- | --- |
| VIP 0 | any | 0.1% / 0.1% | 0.09% / 0.09% | [Open account](https://bit.ly/GateVIP) |
| VIP 1 | 60,000 | 0.099% / 0.099% | 0.089% / 0.089% | [Open account](https://bit.ly/GateVIP) |
| VIP 2 | 120,000 | 0.098% / 0.098% | 0.088% / 0.088% | [Open account](https://bit.ly/GateVIP) |
| VIP 3 | 240,000 | 0.097% / 0.097% | 0.087% / 0.087% | [Open account](https://bit.ly/GateVIP) |
| VIP 4 | 500,000 | 0.095% / 0.096% | 0.086% / 0.086% | [Open account](https://bit.ly/GateVIP) |
| VIP 5 | 1,000,000 | 0.09% / 0.095% | 0.081% / 0.085% | [Open account](https://bit.ly/GateVIP) |
| VIP 6 | 3,000,000 | 0.085% / 0.09% | 0.076% / 0.081% | [Open account](https://bit.ly/GateVIP) |
| VIP 7 | 8,000,000 | 0.08% / 0.085% | 0.07% / 0.076% | [Open account](https://bit.ly/GateVIP) |
| VIP 8 | 20,000,000 | 0.075% / 0.08% | 0.06% / 0.072% | [Open account](https://bit.ly/GateVIP) |
| VIP 9 | 50,000,000 | 0.07% / 0.075% | 0.05% / 0.068% | [Open account](https://bit.ly/GateVIP) |
| VIP 10 | 100,000,000 | 0.04% / 0.058% | 0.04% / 0.058% | [Open account](https://bit.ly/GateVIP) |
| VIP 11 | 120,000,000 | 0.03% / 0.045% | 0.03% / 0.045% | [Open account](https://bit.ly/GateVIP) |
| VIP 12 | 240,000,000 | 0.02% / 0.037% | 0.02% / 0.037% | [Open account](https://bit.ly/GateVIP) |
| VIP 13 | 440,000,000 | 0.01% / 0.03% | 0.01% / 0.03% | [Open account](https://bit.ly/GateVIP) |
| VIP 14 | 800,000,000 | 0.008% / 0.023% | 0.008% / 0.023% | [Open account](https://bit.ly/GateVIP) |
| VIP 15 | 1,600,000,000 | 0% / 0.02% | 0% / 0.02% | [Open account](https://bit.ly/GateVIP) |
| VIP 16 | 3,000,000,000 | 0% / 0.0175% | 0% / 0.0175% | [Open account](https://bit.ly/GateVIP) |

Per-trade rates, spot market. Alpha stays at 0.8% throughout and isn't included above.

Three things in that table aren't obvious from the columns.

Zero maker doesn't arrive until VIP 15. Fifteen tiers of volume or token holdings separate a brand-new account from the 0% maker rate that some exchanges advertise as standard.

VIP 15 and VIP 16 aren't really volume tiers. Gate states that regular VIP users can't be upgraded into them, and that accounts where API volume is at least 60% of the total get moved to senior institutional pricing automatically. They exist on the schedule as a ceiling, not as a realistic target.

The 24-hour withdrawal limit moves with your tier, not your identity-verification level. It sits at 3,000,000 USD at VIP 0, rises to 5,000,000 at VIP 5, 8,000,000 at VIP 9, 10,000,000 at VIP 12, and runs up to 50,000,000 by VIP 16.

There's also a cheaper path than grinding volume. VIP 1 needs 50 GT held on a 14-day average, or roughly 2,000 USD of qualifying assets, or 60,000 USD of 30-day volume. The GT route scales as you climb — 200 GT for VIP 2, 500 for VIP 3, 1,000 for VIP 4, 2,000 for VIP 5, 5,000 for VIP 6 — and the top of the ladder lists 800,000 GT at VIP 13 and 1,500,000 GT at VIP 14.

Holding GT to reach a tier is a real capital position in a token whose price moves independently of your trading. If GT halves, your fee discount cost you 50% of the stake you parked to get it. That's a different kind of cost than simply trading more.

## How Gate actually calculates your tier

Gate doesn't count every dollar of volume equally. The 30-day total is a weighted sum:

- Spot trading, including convert: 100%
- Stock trading: 100%
- USDT and BTC perpetuals, plus USDT delivery futures: 40%
- USD1 contracts: 20%
- Options: 20%
- CFD contracts: 10%

Copy-trading volume in spot and futures counts toward the same totals. So a futures trader needs 2.5 times the notional turnover of a spot trader to land on the same tier, and a CFD trader needs ten times. If you're deciding where to concentrate activity to hit a threshold, that weighting matters more than the raw numbers.

The GT track is measured as your daily average holding over the previous 14 days, including GT2, and it counts balances across spot, margin and Earn products — parking GT in a flexible savings product still counts toward the snapshot while it earns.

👉 [Create your Gate account and check where the 30-day weighting lands you](https://bit.ly/GateVIP)

## Futures fees, briefly

Base USDT-margined perpetual pricing is 0.020% maker and 0.050% taker at VIP 0, and the taker side steps down as you climb: 0.0480% at VIP 3, 0.0450% at VIP 5, 0.0375% at VIP 7, 0.0300% at VIP 10, 0.0240% at VIP 13, 0.0220% at VIP 14.

From VIP 15 the taker rate splits into three contract groups rather than one number. Group A covers BTC, ETH, SOL and XRP perpetuals. Group B is a long list including BNB, DOGE, LINK, LTC, AVAX, SUI and TON. Group C is everything else. Only the top two tiers see different rates across those groups — VIP 15 pays 0.0180% on Group A and 0.0220% on Group C.

Futures fees are charged when you open, close or reduce a position, never on a cancelled or unfilled order, and they're calculated on position value, not on the margin you posted. Leverage doesn't change the rate, it just makes the position value bigger.

One cost that isn't a Gate fee at all: funding. Perpetuals settle funding between longs and shorts, Gate doesn't collect it, and it can run against you or in your favour. A position held for days can rack up more in funding than in trading fees, which is the single most common surprise for anyone new to perpetuals.

Options show a base VIP 0 rate of 0.0200% maker and 0.0280% taker following Gate's February 2026 options adjustment.

## Deposits, withdrawals, and the fees that aren't on the fee page

Crypto deposits cost nothing on Gate's side. You still pay the network's gas, and Gate's deposit table flags some networks as deposit-disabled, which is the field to check before sending rather than the fee column.

Withdrawals are priced per coin and per network, adjust with network congestion, and typically refresh hourly. Gate shows the exact fee and minimum when you submit the request, so the number to look at is the one in front of you, not a figure from an article. Picking a cheaper chain for the same asset is the largest single lever most people have on their total cost, and it's a bigger one than shaving a basis point off a trading fee.

And the cost Gate never charges: slippage. Market orders on thin pairs pay for themselves twice. Scheduling trades when the book is deep is free to do and frequently beats a fee tier upgrade.

## What this costs at realistic volumes

Spot, taker flow, one month:

| Monthly volume | VIP 0 standard | VIP 0 with GT |
| --- | --- | --- |
| 10,000 USD | 10 USD | 9 USD |
| 100,000 USD | 100 USD | 90 USD |
| 500,000 USD | 500 USD | 450 USD |

Scale the 500,000 USD row across a year and you're comparing roughly 6,000 USD against 5,400 USD. Jumping to VIP 5 via 1,000,000 USD of 30-day volume cuts the taker rate to 0.095%, and the same 500,000 USD month bills 475 USD.

That's the shape of it: for casual trading, the fee schedule is noise next to spread and slippage. For anyone turning over six figures a month, it's a line item worth an afternoon of planning.

## The new-user side

Gate's Rewards Hub runs a tiered new-user package. The published tasks are registration and login, identity verification, a first deposit, a first spot or futures trade, and a first app download, with separate reward pools for each. The headline figure varies by region and campaign version, and the deposit and trading thresholds move with it, so check the tasks on the Rewards Hub page in your own account rather than trusting a number from a guide, including this one.

Beyond that, there's an advanced trading track with larger rewards tied to net deposits and cumulative volume, and some rewards are issued as position vouchers or futures fee-rebate coupons rather than withdrawable cash. Worth reading the terms before you plan around them: fee-rebate coupons apply to futures taker fees at a stated rate, and vouchers typically need volume before they unlock.

Gate's referral programme pays 40% commission on the fees your invitees generate, which is a different proposition from the welcome package and worth knowing if you're the person doing the inviting.

👉 [Sign up on Gate and see which new-user tasks are live in your region](https://bit.ly/GateVIP)

## Short answers

**What are Gate's spot fees for a new account?** 0.10% maker and 0.10% taker, both identical, dropping to 0.09% on both sides when fees are paid in GT.

**What are the futures fees?** 0.020% maker and 0.050% taker on USDT-margined perpetuals at VIP 0, with the taker rate falling to 0.0175%-adjacent levels through the tier ladder and separate contract-group rates at VIP 15 and 16.

**Is the 0.2% figure I found correct?** It matches the pre-April-2026 schedule and some older Gate pages. Current billing is 0.1% at VIP 0.

**How do I pay less without trading more?** Hold GT (50 GT reaches VIP 1), enable GT deduction, use limit orders knowing they don't get a discount until VIP 4, and keep stablecoin swaps on the USDC/USDT pair where both sides are free.

**What actually costs the most?** Usually withdrawal network fees and futures funding, in that order, for anyone who isn't a high-frequency spot trader.
