---
title: "Post Mortem 2021"
date: 2021-12-30T19:02:24-05:00
draft: false
categories: ["portfolio"]
---

### Performance

My 2021 time-weighted return was 28.9%, putting me squarely in the who-gives-a-fuck category.

![perf2021](/images/perf2021.png)

I got lucky and it could've been much worse, as I pretty much lost my marbles during the GME saga and made some speculative greedy bets that ended up evaporating about 30% of my portfolio.

On the other hand, I turned a shit ton of rocks in the remainder of the year and managed to grind my way to profitability thanks to a few gems that saved my ass.

I am currently sitting on about 7% in cash, excluding emergency funds.

With that said, and while I'm happy to have made some money, the % return is not that important to me. 

I am not far from the S&P 500 total return, which can either be depressing or encouraging, depending how you want to look at it. I choose to view it as a positive, as I learned so much this year about so many different topics. 

My main goal however is to reach financial freedom one day, and to track my progress towards this goal, I have devised a metric that I call the "Freedom Score".

### The Freedom Score

What I want to know is:

_What is the probability that the passive returns from my portfolio can cover my family's living expenses until I die?_

Technically speaking, I should calculate the probability until both me and my wife die, but I'll let her figure this shit out once I'm gone (or I'll update the calculation next year).

I start by downloading the mortality table for Canadian men from [here](https://www150.statcan.gc.ca/n1/pub/84-537-x/2020001/xls/2017-2019_Tbl-eng.xlsx).

I know what our annual expenses are, and I'm gonna assume 2% inflation until I'm 65 and 1% thereafter. I will also assume I can get a 4% after-tax nominal return from my portfolio (e.g. dividends).

Starting with the value of my portfolio today, every year, I will grow it by 4% and substract the living expenses, until there's no more money in the portfolio.

Then the question (inverted) becomes: what is the probability that I die before the portfolio is drawn down to zero?

In google sheets, it looks like this (Px is the probability of survival on a given year):

![freedom-score1](/images/freedom-score-1.png)

The row highlighted in yellow is the year where the portfolio has been completely drawn down:

![freedom-score2](/images/freedom-score-2.png)

The 8.3% probability in the rightmost cell represents my odds of dying before then, i.e. before there's no money left in the portfolio, which is the same as the probability of my starting portfolio being enough to pay for all expenses until I die.

So, at the end of 2021, my freedom score is 8.3%.

Interestingly, $2.5M is about the portfolio value I would need for my Freedom Score to jump to 100% next year. This figure is probably way too optimistic, as I think it's very likely that I severely underestimated my expense inflation in the future.

So yeah, I won't ditch my job once I reach $2.5M. But at $5M...I'll seriously consider it!

### Justification for the Freedom Score

The reason this score is much better than any portfolio return metric is that it also includes (and benefits from) the savings and contributions I make every year from my salary or any other income.

If I increase my income or my savings ratio, and move those savings to my investing portfolio, it will increase the score.

If I achieve good investment returns from the portfolio, it will also increase the score. 

But the point is that I have three levers at my disposal to reach freedom:

- increasing savings
- reducing expenses
- improving investment returns

### Plan for 2022

I'm looking to increase my cash position as I'm feeling uneasy about the global situation coming out of covid (should we finally come out of it). I feel that there's a crisis of meaning that has been brewing for some time in the U.S., which could coincide with a worldwide energy crisis, mistimed interest rate hikes, tensions with China, etc. I tend to fall a bit on the paranoid side, so I don't take all this too seriously, it's just some stuff I want to keep an eye on if I can, and maybe there are some 2nd-level implications I can think through.

On a more positive note, I want to focus on two specific investment categories in 2022: compounders and disruptors. I have enough macro-driven stocks, cheap turn-arounds and other random stuff.

I'll be looking for wonderful companies and exceptional leaders that can defy the rule that all things naturally decay from entropy (that's my definition of compounders), as well as established or emerging monopolies/oligopolies. This last phrasing is borrowed from Yen Liow, you can catch an amazing podcast where he explains this concept [here](https://www.youtube.com/watch?v=Ei03z7-aIJg).

Finally, I want to be more disciplined about my learning process: read more books and listen to more podcasts, and more importantly take more notes.

On this, I wish you a Happy New Year and a joyful, purpose-driven 2022. I also want to express my heartfelt gratitude to every fintwit or commonstock account I ever interacted with. Thank you for all the learnings and I hope to be of value to you as well in the future.