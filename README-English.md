# COVID 19 Confirmed Cases Analysis
Based on a guided project on Coursera almost 3 years ago, I have decided to revisit the analysis and add some of my own questions that arose from my curiosity about how the situation in my country, Ecuador, unfolded during the pandemic. *Project in progress.

## Technical Details
### About the Dataset
For this project, I used data on daily confirmed total COVID-19 cases from January 22 to April 30, 2020, from all countries worldwide, in CSV format (Available in this repository). The data was obtained from Coursera Project Network.

### About the Language and Environment
Jupyter Labs in Anaconda was used as the environment for conducting the analysis, with Python as the programming language. The file is in .ipynb format.
Libraries used: numpy, pandas, seaborn, matplotlib, plotly, datetime, calendar

## What Do I Want to Discover with This Analysis?
I aimed to focus this analysis on Ecuador's situation during the early months of the pandemic, intending to identify:
- The evolution of daily confirmed total cases from January to April.
- The evolution of daily new confirmed cases within 24 hours during the same period.
- How Ecuador's daily infection rate compares with other countries in Latin America.
- How this same parameter compares with other countries worldwide.
- The top 10 countries that recorded the highest number of new confirmed cases within 24 hours worldwide.
- Additional data on when and how much the peak of infections occurred for a particular country.

## Key Findings
- Confirming what was reported in local news, the first confirmed cases of COVID-19 in Ecuador, Argentina, and Brazil began to be reported at the end of February and the beginning of March 2020. For a few days, Ecuador even surpassed Brazil in the number of confirmed cases, despite the latter country reporting its first cases earlier. This finding supports what was reported nationally during those days: Ecuador was facing serious problems with its healthcare system to deal with the pandemic, and infections started to spiral out of control very quickly.

<p align="center">
  <img src="https://github.com/Karen-Benites/COVID-19-Confirmed-cases-analysis/blob/main/Pictures/Confirmed%20cases%20over%20time%20for%20three%20countries.png">
</p>

- Comparing the daily infection rate of these same three countries, we can see that Brazil has a sustained and very high growth in daily infections compared to Ecuador and Argentina, except for one day in April 2020 when Ecuador far exceeded the other two countries in the number of new cases in a single day. This caught my attention because it was the second time I had seen a remarkable behavior for my country compared to other countries in Latin America. This led me to want to see the evolution of confirmed cases in other countries worldwide and compare it with Ecuador.

<p align="center">
  <img src="https://github.com/Karen-Benites/COVID-19-Confirmed-cases-analysis/blob/main/Pictures/Daily%20Infection%20rate%20comparison%20(3%20countries).png?raw=true">
</p>

#### The tragedy experienced in Ecuador during the early months of the pandemic
- What started with a simple curious question ended up revealing surprising results to me. That peak of new infections in a single day in Ecuador was not only one of the highest in the region but also one of the highest worldwide. Surpassing even European countries like Spain, the UK, and Brazil in Latin America. Now it makes sense why we made international headlines in those dark days of the pandemic. The memories of dozens of people dying suddenly in the streets, with thousands of new infections being reported every day, were a traumatic event for the country and a symbol of the total inefficiency of the healthcare system, which quickly collapsed in the face of this unexpected situation. Data like this leads us to an important reflection on the need to invest in the public healthcare system and avoid similar tragedies in the future.

<p align="center">
  <img src="https://github.com/Karen-Benites/COVID-19-Confirmed-cases-analysis/blob/main/Pictures/Top%2010%20countries%20with%20highest%20COVID%2019%20new%20cases%20under%2024%20h.png">
</p>

## What's Next?
I plan to further expand this analysis by adding the following elements:
- Comparison with other factors such as happiness indices by country, GDP per capita, etc.
- Comparison of the number of daily confirmed total cases with the number of daily confirmed deaths, and see how much the top 10 changes on a global level.
