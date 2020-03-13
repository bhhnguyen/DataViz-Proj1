**Team Name**: Stock Junkies

**Group Members**: James Barranza, Margeaux Jensen, Wendy Meyer, Benji Nguyen

Broadly, we're interested in the effect of the coronavirus on stock prices across multiple industries. We're interested in observing who's most and least affected and looking at the discrepancies across these various industries. We're interested in looking at average stock differences before and after around December 2019 (or whichever we decide to use as the 'start date' of the epidemic) and plan to analyze this at an industry level (the groupings will be determined by whichever API we settle on using). We'll be looking at information in the months leading up to ~Dec 2019 and will have several months after that to look at the differences.

We have a few theories on which industries are affected negatively (e.g. travel, hotel, restaurants) and what may not be very affected (large tech companies). Some questions we're looking to answer: Which industries are most affected? Which are least affected? What specific companies are most affected? About where do we see the effects starting? We're also looking to include data on Coronavirus prevalence to see if we can draw a connection between that and the stock market impact.

To accomplish this, we'll be using stock price and company profile information from a finance data API like IEX Cloud or Alpha Vantage. Both of these sources provide realtime data on stock market information and each have information on various company profiles. Each company is tagged with an industry-level tag so this will be our primary means of determining industry.

IEX Cloud
https://iexcloud.io/

Alpha Vantage
https://www.alphavantage.co/