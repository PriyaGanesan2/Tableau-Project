# Final-Project-Tableau

## Project/Goals
Leverage Tableau to conduct a comprehensive analysis of Canada's real estate landscape over the last 40 years, addressing key questions and providing valuable insights using graphs. Utilize appropriate visualizations to showcase trends, comparisons, and correlations within the data. Ensure accuracy in unit consistency and focus on extracting meaningful patterns, trends.


## Process
### (your step 1)
Step 1: Leverage Excel and Python to explore and clean the data (remove null, remove special characters after JSON extract, etc)

### (your step 2)
Step 2: Import the Cleaned dataset into Tableau
### (step 3)
Step 3: Developing visualizations and trends to explore the dataset to answer the questions 

## Results
1. Option selected - 1
2. Show the trend of house prices across Canada in the last 40 years (table housing_price_index).
   ![image](https://github.com/PriyaGanesan2/Tableau-Project/assets/110922792/3cd0045c-cb3b-41ac-bc1c-fb622680a2ba)
   Housing Price Trendshows fluctuations, with significant increases in housing price in the 1980s to 1990s and from 2004-2010. 


4. Compare the trend after 2005 with actual benchmark prices in table real_estate_prices to see if there are any differences.
   ![image](https://github.com/PriyaGanesan2/Tableau-Project/assets/110922792/d61d7ef3-7f3a-49b9-ac07-c405c78b0b06)
    The graph shows no difference in the trends between actual and benchmark real esatte pricing index. 

6. Compare this trend with the trend of office prices. Which one is getting more expensive, faster?

   ![image](https://github.com/PriyaGanesan2/Tableau-Project/assets/110922792/36885e6a-4eea-4560-8db2-f7fb015eecb2)
   Office spaces have been pricier than houses, with housing prices slowly catching up from 2016.

   
8. Create a heatmap of Canada with current house prices for each available district.
![image](https://github.com/PriyaGanesan2/Tableau-Project/assets/110922792/a1e45b20-35e3-4208-994c-542be2729e52)
Geo Heat Map shows 
Ontario, Newfoundland, and British Columbia lead in real estate with higher property values.


10. Are the price differences between different districts increasing?
![image](https://github.com/PriyaGanesan2/Tableau-Project/assets/110922792/9674dea3-f8b6-4774-b011-ef8f10033767)
The graph shows similar real estate pricing index across canada with little fluctuation until 2019, after which particularly noting a change in the housing price index for Alberta around 2019.

11. Compare the trend of house prices with earnings. *In case you want to plot monthly salary, be aware that the earnings value is per week.
![image](https://github.com/PriyaGanesan2/Tableau-Project/assets/110922792/d4427f45-4c40-4cbb-8774-0f4282d80347)
House Affordability declined after 2006, with a consistent increase in housing prices. 


12. There were several economic crises in the world in the last 40 years, including these four: Black Monday (1987), Recession (early 1990s), dot com bubble (2000 - 2002), Financial crisis (2007 - 2009). Show the effect of these crises
![image](https://github.com/PriyaGanesan2/Tableau-Project/assets/110922792/ba83c3bb-408b-4f1b-85ff-8f780fab5472)
Impact of key economic crises in the last 40 years.
Real estate prices experienced a drop during the 1990 recession and the financial crisis.
Additionally, we can see a dip in Consumer Price Index during the financial crisis.


13. Plot consumer_index together with housing_price_index and fit the regression line between them. Can we predict consumer_index from the housing_price_index?
![image](https://github.com/PriyaGanesan2/Tableau-Project/assets/110922792/b6bd89bb-9659-46d3-a8e6-3162f72fb8d4)
The trend line shows  strong correlation, emphasizing the significance of Housing Price in predicting the Consumer Price Index Value(CPI)
Linear trend involving Housing Price and Consumer Price Index exhibited a significant correlation (p < 0.0001), with an R-Squared value of 0.70.


14. Try to find an interesting pattern, trend, outlier, etc. from the data used in the above questions.
HINT : Double check all units in the table before any comparison.
![image](https://github.com/PriyaGanesan2/Tableau-Project/assets/110922792/2e812ba5-1ce6-48ac-9dbb-a29a25849e4b)
Housing Construction
1960s to the early 1980s, there is a noticeable rise in housing construction and completed projects

15. ![image](https://github.com/PriyaGanesan2/Tableau-Project/assets/110922792/744ffb35-5e97-4418-877d-27b1372293de)




## Challenges 
(discuss challenges you faced in the project)
1. Selecting appropriate visualization graph to convey the intended message
2. Making sense of data, especially in the consumer index table 


## Future Goals
(what would you do if you had more time?)
1. Demographic Impact: Investigate how factors such as population growth, age, and immigration patterns influence real estate trends
2. Comparative Analysis with Global Markets: Conduct analysis of real estate trends in Canada with other global markets and identify patterns

