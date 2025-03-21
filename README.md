![](assets/eBay_logo.png)
# E-commerce Analytics

# 1: ASK  
The **Ask** phase aims to determine and define the question that needs to be addressed and to understand stakeholder expectations. This process sets the foundation for the rest of the data analysis.  

## 1.1: Define the Business Objective  
This analysis aims to explore my sales data from eBay, an e-commerce marketplace, to gain insights into increasing sales. A glance at the data reveals a significant drop in sales from **Q3 to Q4** over the past four years. Various factors influence buyer decisions in e-commerce, but this analysis will focus on **seasonal sales trends** to provide actionable insights for boosting Q4 sales and preventing a sharp decline.  

## 1.2: Key Stakeholders  
Since this is my business and data, I am the sole stakeholder in this analysis.  

## 1.3: Guiding Questions   
- **Which categories contribute most to revenue and overall sales performance?**  
- **Does offering free shipping influence total revenue and profit?**  
- **What percentage of sales come from repeat customers, and how do they impact profitability?**  
- **What periods (months, weeks, or days) see the highest and lowest sales? Are there any unexpected seasonal dips?**  
- **How do seasonality and specific holidays/events (e.g., Black Friday, Christmas, Back-to-School) impact purchasing behavior?**  

---

# 2: PREPARE  
In the **Prepare** phase, we examine the data to assess its **structure, credibility, and relevance** for answering the business questions.  

## 2.1: Data Source  
- **Name**: eBay Sales Data  
- **Source**: My personal sales data  
- **Description**: This dataset contains my personal sales data from **January 2021 to September 2024**. Each row represents an item sold during this period, including variables such as:  
  - **Transaction details**: Transaction date, type, order number  
  - **Location information**: City, state, zip code, country  
  - **Financials**: Net amount, item subtotal, shipping & handling, collected tax, final value fees (fixed & variable), international fees, and gross transaction amount  
  - **Product details**: Item ID, item title, quantity, and category  

## 2.2: Downloading the Data  
For this case study, **Python (Pandas)** will be the main tool for data analysis. The dataset will be used in **CSV format**, labeled as:  
- `eBay_Sales_Data.csv`  

## 2.3: Data Credibility and ROCCC Assessment  
I will use the **ROCCC** framework to assess the dataset's reliability and potential biases.  

- **Reliable**: ✅ Yes, the dataset comes directly from my eBay sales records.  
- **Original**: ✅ Yes, the dataset is a first-party data source, not third-party or estimated data.  
- **Comprehensive**: ✅ Yes, the dataset covers a broad range of performance factors, providing enough information to create reliable insights.  
- **Current**: ✅ Yes, the dataset includes data from the past **four years (2021–2024)**.  
- **Cited**: ✅ Yes, the data is properly sourced and reliable.  

---

# 3: PROCESS  
In the **Process** phase, we ensure our data is clean by correcting or removing **inaccurate, corrupted, improperly formatted, duplicate, or incomplete entries** within the dataset.  

## 3.1: Reviewing Our Data in Python  
In this section, we will load and review the dataset using **Pandas** to check for:  
- Missing values  
- Duplicates  
- Data type inconsistencies  
- Formatting errors  

```python
import pandas as pd

# Load dataset
df = pd.read_csv("eBay_Sales_Data.csv")

# Display basic info
df.info()

# Check for missing values
df.isnull().sum()
