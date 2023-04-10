# Introduction

There has been a rise in e-commerce and content creator all around the world. E-commerence is a type of business where the company buy and sell products and services on the internet<a href="https://www.investopedia.com/terms/e/ecommerce.asp" target="_blank"><sup>1</sup></a>.  Content creator, sometime known as influencers, is where one generate money through the use of content to communicate with their target audience<a href="https://www.adobe.com/express/learn/blog/content-creator#:~:text=A%20content%20creator%20is%20someone,earn%20revenue%20through%20your%20efforts." target="_blank"><sup>2</sup></a>. 
<br><br>
Before the company starts the e-commerence business, they will first target which market they want to sell the products to. In the world of e-commerence, they will choose of the Big 4 countries market, namedly, United States, Canada, United Kingdom(UK) and Australia. Once done, the company will begin doing market research on the proudcts and servies they want to sell and what is the current trend of selling products. Some of the ways the company do market research is the use of Google Trend. With the market research data, the company will then know what to focus on, how to plan their budget and whether is it cost effieient for the business to place their advertisement. This will overall result in increased sales and profit.
<br><br>
For content creator, they usually need to find ideas to generate content for the right target audience to earn a living, many of them faces creator's block where they are unable to generate creative content/ideas <a href="https://www.freepik.com/blog/improve-creativity-beat-creators-block/#:~:text=Just%20like%20writer's%20block%2C%20creator's,the%20patience%20for%20creator's%20block." target="_blank"><sup>3<sup></a>.
For that, they usually look for the trending topics or things that are currently in the trend. Google Trend can be one of the ways to generate ideas for content creators. 
<br><br>
For this project, I will be focusing on Canada and Google Trend will be used. Canada is chosen as it has lower tax rate as compared to the other 3 companies <a href="https://www.nysaglobal.com/blog/what-makes-canada-a-great-country-to-start-a-new-business/#:~:text=Canada%20maintains%20one%20of%20the,means%20increased%20profitability%20and%20success." target="_blank"><sup>4<sup></a>.


# Problem Statement

For this project, there are 2 things to find: 
- trending searched terms
- top searched terms

With these data, the start up e-commerence will then know what to focus on and this will overall result in increased sales and profit. For content creators facing creator's block, they can use the result above to catch the attention of their target audience and at the same time, generate more income.


# Data Source, Data Cleaning & EDA

The Google Trends datasets are taken from Big Query. Big Query is a data warehouse cloud platform developed by Google itself. It is free for public to use and SQL is used to clean and query the required data. The data is then saved as csv file for analysis. As I am using the free version of Big Query, there is a limit to much I can use SQL for cleaning, data wrangling analysis and visualisation. Therefore, I used both Excel's power query and tableau for additional cleaning, data wrangling analysis and visualisation.

# Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**region_name**|object|Big Query|Region in Canada.| 
|**month**|int64|Big Query|Month of 2022.| 
|**rank**|int64|Big Query|The rank of the top terms and it is updated everyday.| 
|**percent_gain**|int64|Big Query|Percentage gain (rate) at which term rose compared to previous date period.| 
|**term**|object|Big Query|The human readable identifier for a term, i.e. 'Acme Inc'.| 
|**score**|int64|Big Query|Presents the maximum search interest of the term for the time and location selected. The index of the value 100 will imply that in the specified time range, a specific term was trending mostly where the peek is, i.e. where the score was highest.| 
|**category**|object|Excel|Category of the term.| 
 


# Dashboard

Check out the <a href="https://public.tableau.com/app/profile/jimmy5898/viz/GoggleTrendsinCanada2022/Dashboard">dashboard</a> that was done using Tableau!


# Limitation

As this was based on the year 2022, it might not be the same for 2023. Therefore, more studies and data are required. Previous years were not taken in to consideration as comsumer behavior have changed after covid <a href="https://www.mckinsey.com/industries/paper-forest-products-and-packaging/our-insights/beyond-covid-19-the-new-consumer-behavior-is-sticking-in-the-tissue-industry." target="_blank"><sup>5<sup></a>. Therefore, results based on previous years are not a good estimate of the future.


# Conclusion & Recommendation

Based on the dashboard, the following are the findings:
- "TSX today", where TSX stands for Toronto Stock Exchange, which is a stock, is the most searched term in 2022 
- "Adobo", a popular Filipino dish, is the fastest rising searched term in 2022

This means that:
- start up e-commerence should either centre their business to either finance categorey such as stocks or on food to increase their sales and profit
- content creator can generate idea based on finance or dish to attact more target audience and therefore, increase their income.


# Future Directions

To further improve the results, a recommender system based on machine learning model (Supervised, UnSupervised and deep learning) can be impletmented but it will be under the future project.