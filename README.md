# JPM Healthcare Conference 2019
Motivation: The 2019 JP Morgan Healthcare Conference draws to a close and it got me wondering how much of an impact this conference has on healthcare stock value fluctuations. It's well known that stocks change in response to the speeches, deals, and data presented at the meeting. I've found some sources that attempt to quantify the impact of the meeting on stocks (see below). But I wanted to (a) ask the specific questions below, (b) work with financial data for the first time in R, and (c) practice using tidy data approaches. 

I hypothesize that:   
1. Healthcare stock prices tend to fluctuate more during JPM week than any other week in the same year.   
2. The biotech sector outperforms the S&P 500 during JPM week more often than is expected by chance.  

Example quantification of impact of JPM week on biotech stocks: [https://www.cnbc.com/2017/01/04/betting-on-biotech-during-jpmorgans-big-health-care-conference-pays-off-history-shows.html]  
Quotes:  
*"Biotech has historically outperformed the broader market during The J.P. Morgan Healthcare Conference"  
*"In the past 16 years, the NYSE Arca Biotechnology index (BTK), which measures the performance of 30 biotechnology firms, has outperformed the S&P 500 index by nearly 3 percent during JPMorgan's conference"  

The analysis presented in the accompanying code and plots is highly preliminary. Advice from people familiar with analyzing finanical data is most welcome. 
