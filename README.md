# Customer Shopping Trends Analysis (EDA Project)

## Project Overview
This repository contains an Exploratory Data Analysis (EDA) on a customer shopping trends dataset. It uncovers patterns in purchases, demographics, and behaviours using Python for data manipulation and visualization, as well as statistical methods. The aim is to understand who the customers are, what items  they are purchasing, the frequency of their purchases, spending patterns across demographics, what mode of payment is mostly employed, and what relationships and trends exist in the dataset. This is to draw meaningful business insights that can support and maximize marketing strategies, inventory, and sales optimization.

## Objectives
The main questions answered in this analysis include:
1. Who are the customers?
2. What products do they buy the most?
3. When and how often do customers purchase?
4. Are there spending patterns by gender, age, location, or category?
5. What is the preferred payment method?
6. What relationships and trends can be derived from the data?

## Dataset Descriptions
The dataset is sourced from a public dataset (Kaggle's shopping trends data), which includes 3,900 records with the following columns :
1.__Customer ID__: Unique identifier assigned to each customer.
2.__Age__: Age of the customer at the time of purchase.
3.__Gender__: Gender of the customer.
4.__Item Purchased__: Specific product purchased by the customer.
5.__Category__: Product category to which the purchased item belongs (e.g., Clothing, Footwear).
6.__Purchase Amount (USD)__: Monetary value of the transaction in US dollars.
7.__Location__: Geographic location (state) of the customer.
8.__Size__:Size of the purchased item.
9.__Colour__: Color variant of the purchased item.
10.__Season__: Season during which the purchase was made.
11.__Review Rating__: Customer’s rating of the purchased item.
12.__Subscription Status__: Indicates whether the customer is subscribed to a membership or service (Yes/No).
13.__Shipping Type__: Mode of shipping selected for the order.
14.__Discount Applied__: Indicates whether a discount was applied to the purchase (Yes/No).
15.__Promo Code Used__: Indicates whether a promotional code was used (Yes/No).
16.__Previous Purchases__: Number of purchases made by the customer before the current transaction.
17.__Payment Method__:Payment method used to complete the transaction.
18.__Frequency of Purchases__: How often purchases are made

## Technologies and Tools
- **Pandas**: Data loading, cleaning, analysis.
- **Seaborn/Matplotlib**: Visualizations (histograms, box plots, heatmaps).
- **NumPy**: Numerical computations.
- Jupyter Notebook for interactive EDA.

## Data Preparation
Before the analysis, the following were done to ascertain the validity of the dataset
1. Inspection of the shape of the dataset to know the number of columns and rows
2. The data types
3. Duplicates and missing values
Data Cleaning: This dataset was largely clean and met the required standard for the analysis

## Exploratory Data Analysis (EDA)
The analysis performed involves:
**Customer Demographics**
Distribution of customers by gender and age group
Customer concentration across different locations
**Product Preferences**
Most purchased product categories
Popular items across demographics
**Spending Behaviour**
Average spending by gender and age
Spending variation across product categories
**Purchase Patterns**
Seasonal trends in shopping
Purchase frequency distribution
**Payment Insights**
Most preferred payment methods
Differences in payment choice by customer segment
**Relationships and Trends established**
Correlation of numerical variables to measure the level of the relationship
Trend of spending pattern by category and gender

## Visualizations 
The notebook includes multiple visualizations, such as:
*Bar charts for category popularity
*Histograms of customer age and spending
*Heatmaps showing relationships between variables
*Trend charts for seasonal shopping behavior
*Payment method distribution plots
   
## Key Insights
1. The customer base consists  mostly of middle-aged shoppers from different age groups and states, with a strong male skew.
2. The top purchased categories are clothing, footwear, and accessories, which together dominate sales.
3. Purchases occur year-round with a clear seasonal pattern, and most customers buy quarterly.
4. Spending shows variation across gender, age group, location, and product category.
5. Payment preferences are fairly evenly distributed across available methods, showing no extreme dominance by any single option.
6. Overall, correlations between numeric variables in the dataset are generally weak, indicating that most relationships are not particularly strong or predictive.

## Recommendation
1. Marketing efforts should focus on addressing key demographic gaps in the current customer base.
2. Strengthen inventory around clothing and footwear as the main drivers, lift outerwear sales through smart bundling and cold-season promotions, and fine-tune size and colour stocking (medium + neutral/diverse) to better match actual demand patterns.
3. Heavy  investment should be made in fall and winter for maximum revenue capture, and use targeted, time-limited flash sales and bundles in spring and summer to
 sustain activity and frequency while protecting margins and appealing to less price-sensitive shoppers.
4. Promote PayPal and credit card usage for easier checkout while retaining other payment options.
5. Other analyses, like predictive, A/B tests, Customer segmentation, and market basket analysis, could be used to attain other useful insights to boost revenue and to drive sustainable growth.
   
