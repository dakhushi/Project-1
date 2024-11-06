# Project-1
Monash Data Analytics Bootcamp Group Project.

***Team 6: Collaborators***

+ [khushi](https://github.com/dakhushi) as a Project Leader
+ [Raymond Tang](https://github.com/Raymond8837)  as a Data Analyst
+ [Napat](https://github.com/dakhushi/Project-1-Team-6/commits?author=NVSung) as a Data Analyst
+ [Kajal Jain](https://github.com/kajalkjain)  as a Data Analyst

## Exploratory Data Analysis for Australia RealEstate Dataset

***Purpose and scope of this EDA:***
The purpose of this EDA is to help the investor to prepare the budget and select the city purchase the property in Australia Cities. 
We are going to explore and analyze a real estate dataset to understand underlying patterns, relationships and trends within the data.

Key Questions and Insights we tried to work upon,

+ Price analysis:
+ 
1.What is the average price of proprties in different cities or states?

2.How does the price distribution look like(ex. are there any outliers)

+ Size and Space Analysis:
1. How does the number of Bedrooms and bathrooms correlate with the size of the property?

+ Year Built Analysis:

1. How does the age of the property affect the price?

3. What are the most common construction years?

+ Type and garage Analysis:

1. What type of properties are most common in different cities or states?

***Challenges we faced:*** 

After importing, exploring and analyzing datasets, we realized that the DataSet does not support analysis to answer the targeted questions. So we decided to change our dataset and focus only on the Northern Territory region of Australia. 

### Northern Territory region -Property price analysis

Purpose and scope of this EDA:
The purpose of this EDA is to help the investor to prepare the budget and purchase the property in Northern Territory. We are going to explore and analyze a real estate dataset to understand underlying patterns, relationships and trends within the data in Northern Territory. We are aiming to identify the factors that affect the house prices.

+ ***About the Dataset:***

This dataset contains information on 1000 properties in the NT region of Australia, including location, size, price, and other details.
This dataset provided us with an excellent opportunity to practice our data cleaning skills and perform multiple analysis to answer our targeted questions.

+ ***Our goal is to answer the following questions:***

+ ***Target Object*** : Price

+ ***Price Distribution :***

1. How does the price distribution look like(ex. are there any outliers

Hypothesis question    :  What is the distribution shape of real estate prices in the northern territories  ?

null hypothesis        : property prices are normally distributed.

Alternative hypothesis : property prices are not normally distributed.

+ ***Property Distribution***

2. Which property type has the highest demand in the Northern Territory market.

Hypothesis Test Question: null Hypothesis : Apartments are more expensive than the unit.

Alternative hypothesis : Apartments are not more expensive than the unit.

+ **Analysis outcome:**
Under the sample data, house is the most common property type (> 300 counts).
Apartment and Unit have similar counts (slightly below 200).
Townhouse has a notable count but is significantly less than House, Apartment, and Unit.
Other property types (Studio, Acreage, Duplex/Semi-detached, Other, Villa) have very low counts, with Villa being the least common.

+ **Conclusion:**
Houses dominate the market, indicating higher availability and preference for this property type.

+ ***Property Feature Analysis***

How do different features influence the price of the property?

Is there any correlation between number of bedrooms and property price?
Yes, formula: y= 195430.08 + 109896.23 * bedroom count. 1 bedroom more, $109k more on the property price. Clear positive correlation observed. Conclusion: More bedrooms generally lead to higher property prices.

1. Is there any correlation between number of bedrooms and property price?

Yes, Positive correlation observed. y= 188292.79 + 184162.97 * bathroom count. 1 bathroom more, $184k more on the property price. 

**Conclusion:** More bathrooms correlate with higher property prices.

3. Is there any correlation between the number of bathrooms and property price?

Yes, Positive correlation observed. y= 188292.79 + 184162.97 * bathroom count. 1 bathroom more, $184k more on the property price.

**Conclusion:** More bathrooms correlate with higher property prices.

6. Is there any correlation between the parking count and property price?

Yes. Positive correlation observed.y= 386281.40 + 52954.85 * parking count. 1 parking more, $52k more on the property price.

**Conclusion:** More parking spaces correlate with higher property prices

+ What is the average listing price of the top ten agencies?

Shown in the Graph, please refer Fig 11


+ What is the market share of the active listing count of top ten agencies?

Shown in the Graph, please refer Fig 10


### Data Source
For Australia Real Estate analysis
https://www.kaggle.com/datasets/smmmmmmmmmmmm/australia-real-estate-dataset

For Northern Territory region -Property price analysis
https://www.kaggle.com/datasets/thedevastator/australian-housing-data-1000-properties-sampled/data

## Refferences:
+ pandas documentation
+ stackoverflow posts
+ https://www.kaggle.com/code/mojtabaameri/australian-housing-prices-eda
+ chat GPT
+ youtube tutorials
+ [Presentation](https://www.canva.com/design/DAGKcclqCgw/PH8Jo1i9jclEd3CP5xk_OQ/edit?utm_content=DAGKcclqCgw&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
