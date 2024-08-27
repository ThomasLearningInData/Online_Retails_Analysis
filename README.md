# Analysis on Online Retails data
Raw dataset: Online Retail.xlsx
| **Purpose**                      | **Skills**                                                            | **Dataset**                     | **Notebook**                          | **Generated New Dataset**           |
|-----------------------------------|-----------------------------------------------------------------------|----------------------------------|---------------------------------------|-------------------------------------|
| Data preprocessing and understanding the data | Data cleaning, feature engineering, EDA, and generate category with AI                             | Online Retail.xlsx               | `EDA-Online-Retail.ipynb`             | `cleaned_Online_Retail.csv`         |
| Explore UK products               | Product return rate analysis and profitability insights                | `cleaned_Online_Retail.csv`      | `products_return.ipynb`               | `UK_return_rate.csv`                |
| Explore customer data             | Customer retention analysis, Generating E-commerce metrics, RFM analysis, and Statistical analysis | `cleaned_Online_Retail.csv`      | `Customer_Analysis.ipynb`            | `rmf.csv`, `cohort_data.csv`        |
| Explore customer behavior         | Churn analysis, price analysis, Customer Segmentation (with K-Means)   | `rmf.csv`, `cohort_data.csv`     | `customer_behaviour_analysis.ipynb`   | `customer_behaviour.csv`            |

Note: I have utilized both OpenAI and Choq (with the Llama3-8B-8192 model) to generate a new category column based on the text data. While OpenAI provides more accurate results, it operates on a paid-per-prompt basis. Choq offers a limited number of free prompts but also requires payment for extended usage. The code for generating the new category column has been included in the EDA-Online-Retail.ipynb notebook. If you'd like to generate the data yourself, you can insert your API key and run the code.

## EDA 
Business insight are listed inside the ipynb file. 

# Monthly Total Revenue and Number of Orders by Country:
![螢幕截圖 2024-08-26 下午7 45 26](https://github.com/user-attachments/assets/feb1dd98-29e3-40fe-9b41-2324d3d673c7)

# Weekday vs weekend purchase
![螢幕截圖 2024-08-26 下午7 46 00](https://github.com/user-attachments/assets/9b065300-9e38-49af-9594-cbb93a889a9a)

# Top 20 Customers by Total Purchases and Total Spend
![image](https://github.com/user-attachments/assets/b143d789-6a03-48e8-9319-ac47d00f5a83)

# Top 20 Customers by Total Spend and Their Number of Purchases
![image](https://github.com/user-attachments/assets/3f5b39b1-d810-4168-8926-f593c7b71539)

# Daily Sales Trends by Country - UK
![螢幕截圖 2024-08-26 下午7 49 09](https://github.com/user-attachments/assets/0dfe2075-4d6b-44ff-ba39-dea0124a4451)

# Most Selling 20 Products
![image](https://github.com/user-attachments/assets/1d7dda9f-79ad-43b2-b2d4-10ddf8691eea)


