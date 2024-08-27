# Analysis on Online Retails data
Raw dataset: Online Retail.xlsx
| **Purpose**                      | **Skills**                                                            | **Dataset**                     | **Notebook**                          | **Generated New Dataset**           |
|-----------------------------------|-----------------------------------------------------------------------|----------------------------------|---------------------------------------|-------------------------------------|
| Data preprocessing and understanding the data | Data cleaning, feature engineering, EDA, and generate category with AI                             | Online Retail.xlsx               | `EDA-Online-Retail.ipynb`             | `cleaned_Online_Retail.csv`         |
| Explore UK products               | Product analysis and profitability insights                | `cleaned_Online_Retail.csv`      | `products_return.ipynb`               | `UK_return_rate.csv`                |
| Explore customer data             | Customer retention analysis, Generating E-commerce metrics, RFM analysis, and Statistical analysis | `cleaned_Online_Retail.csv`      | `Customer_Analysis.ipynb`            | `rmf.csv`, `cohort_data.csv`        |
| Explore customer behavior         | Churn analysis, price analysis, Customer Segmentation (with K-Means)   | `rmf.csv`, `cohort_data.csv`     | `customer_behaviour_analysis.ipynb`   | `customer_behaviour.csv`            |

Note: I have utilized both OpenAI and Choq (with the Llama3-8B-8192 model) to generate a new category column based on the text data. While OpenAI provides more accurate results, it operates on a paid-per-prompt basis. Choq offers a limited number of free prompts but also requires payment for extended usage. The code for generating the new category column has been included in the EDA-Online-Retail.ipynb notebook. If you'd like to generate the data yourself, you can insert your API key and run the code.

## EDA 
Business insight are listed inside the ipynb file. 

### Monthly Total Revenue and Number of Orders by Country:
![螢幕截圖 2024-08-26 下午7 45 26](https://github.com/user-attachments/assets/feb1dd98-29e3-40fe-9b41-2324d3d673c7)

### Weekday vs weekend purchase
![螢幕截圖 2024-08-26 下午7 46 00](https://github.com/user-attachments/assets/9b065300-9e38-49af-9594-cbb93a889a9a)

### Top 20 Customers by Total Purchases and Total Spend
![image](https://github.com/user-attachments/assets/b143d789-6a03-48e8-9319-ac47d00f5a83)

### Top 20 Customers by Total Spend and Their Number of Purchases
![image](https://github.com/user-attachments/assets/3f5b39b1-d810-4168-8926-f593c7b71539)

### Daily Sales Trends by Country - UK
![螢幕截圖 2024-08-26 下午7 49 09](https://github.com/user-attachments/assets/0dfe2075-4d6b-44ff-ba39-dea0124a4451)

### Most Selling 20 Products
![image](https://github.com/user-attachments/assets/1d7dda9f-79ad-43b2-b2d4-10ddf8691eea)

### Correlation
![image](https://github.com/user-attachments/assets/c9599c56-5e38-49af-84dc-3906c7c004de)

### Top 10 Return Rate Products
![螢幕截圖 2024-08-26 下午7 59 56](https://github.com/user-attachments/assets/7e4f1e5a-084b-45c9-8d28-cce0454f38bf)

### Top 10 Performers by Sales Volume
![螢幕截圖 2024-08-26 下午8 01 20](https://github.com/user-attachments/assets/e1d555b9-3475-41eb-aefb-742fd2e8cd42)

### Customer Retention by Monthly
![image](https://github.com/user-attachments/assets/0f1bf3a4-a28a-461b-954d-8ca1eb2c35d7)

### New Customers Acquired Each Day by Country
![螢幕截圖 2024-08-26 下午8 02 24](https://github.com/user-attachments/assets/27e26567-b390-42f0-8d53-1c28e5839a99)

### RFM Score: it has been weighted
![image](https://github.com/user-attachments/assets/69532585-bab6-4600-bdcb-61b9578f2b58)

### Generate label by RFM Score
![螢幕截圖 2024-08-26 下午8 07 29](https://github.com/user-attachments/assets/d399742d-3508-4325-ad8d-3ceebd2b5544)

### Multiple Linear Regression
![螢幕截圖 2024-08-26 下午8 07 54](https://github.com/user-attachments/assets/7370346f-5889-4762-b4aa-c00ace90848f)

### Number of Customers Who Churned at Different Time Periods
![image](https://github.com/user-attachments/assets/fc06d47c-9263-44df-91fa-0743734c33ee)

### Average Product Ratios by Country: it has been weighted
![image](https://github.com/user-attachments/assets/c6e289d4-6fcd-4dd4-8773-9227df4bf351)

### Elbow Method to detect the best number of clusters for KNN (n_clusters=4)
![image](https://github.com/user-attachments/assets/f38c37d2-c5a9-4cd3-a3d2-59e78bc43c79)

### Cluster the customer based on the RFM and product price ratio
![螢幕截圖 2024-08-26 下午8 11 03](https://github.com/user-attachments/assets/a430dd38-9f15-4b36-b683-f747ace22dae)







