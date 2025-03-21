![](assets/eBay_logo.png)
# E-commerce Analytics

# 1: ASK  
The Ask phase aims to determine and define the question that needs to be addressed and to understand stakeholder expectations. This process sets the foundation for the rest of the data analysis.  

## 1.1: Define the Business Objective  
This analysis aims to explore my sales data from eBay, an e-commerce marketplace, to gain insights into increasing sales. A glance at the data reveals a significant drop in sales from Q3 to Q4 over the past four years. Various factors influence buyer decisions in e-commerce, but this analysis will focus on seasonal sales trends to provide actionable insights for boosting Q4 sales and preventing a sharp decline.  

## 1.3: Key Stakeholders  
Since this is my business and data, I am the sole stakeholder in this analysis.  

## 1.4: Guiding Questions   
- **Which categories and products contribute most to revenue, profit, and overall sales performance?**  
- **How do seasonality and specific holidays/events (e.g., Black Friday, Christmas, Back-to-School) impact purchasing behavior?**  
- **Does offering free shipping influence total revenue, profit, or customer purchase decisions?**  
- **What percentage of sales come from repeat customers, and how do they impact profitability?**  
- **Which products and categories have the highest and lowest profit margins?**  
- **What time periods (months, weeks, or days) see the highest and lowest sales, and are there any unexpected seasonal dips? How can they be mitigated?**  

# 2: PREPARE
In the Prepare phase, we examine the data to assess its structure, credibility, and relevance for answering the business questions.

### 2.1: Data Source
- **Name**: eBay Sales Data
- **Source**: My personal sales data
- **Description**: This is my personal sales data from January 2021 to September 2024. The data rows include every item sold between that period of time with variables such as transaction date, type, order number, city, state, zip code, country, net amount, item id, item title, quantity, item subtotal, shipping & handling, collected tax, final value fee fixed, final value fee variable, international fee, gross transaction amount, and category.

### 2.2: Downloading The Data
In this case study, Python Pandas will be the main tool for data analysis. The CSV files that will be used in this case study include:
- `eBay Sales Data`

### 2.3: Data Credibility and ROCCC Assessment
I will use ROCCC to assess whether this data has issues with bias or credibility.

- **Reliable**: Yes, the dataset comes directly from my own eBay sales records.
- **Original**: Yes, the dataset is a first-party data source—not third-party or estimated data.
- **Comprehensive**: Yes, the dataset covers a broad range of performance factors with enought to create reliable inisghts.
- **Current**: Yes, the dataset includes data from the past 4 years (2021 to 2024)
- **Cited**: Yes, the data is properly cited and reliable.

# 3: PROCESS
In the process phase, we ensure our data is clean by correcting or removing inaccurate, corrupted, improperly formatted, duplicate, or incomplete entries within the dataset.

### 3.1: Reviewing Our Data in Python



