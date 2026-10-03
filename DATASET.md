## Details of Features

The details of the features are as follows:

| Feature | Description |
|---|---|
| **Id** | Unique identifier for each individual in the dataset. |
| **Year_Birth** | The birth year of the individual. |
| **Education** | The highest level of education attained by the individual. |
| **Marital_Status** | The marital status of the individual. |
| **Income** | The annual income of the individual. |
| **Kidhome** | The number of young children in the household. |
| **Teenhome** | The number of teenagers in the household. |
| **Dt_Customer** | The date when the customer first enrolled or became a part of the company's database. |
| **Recency** | The number of days since the customer's last purchase or interaction. |
| **MntWines** | The amount spent on wines. |
| **MntFruits** | The amount spent on fruits. |
| **MntMeatProducts** | The amount spent on meat products. |
| **MntFishProducts** | The amount spent on fish products. |
| **MntSweetProducts** | The amount spent on sweet products. |
| **MntGoldProds** | The amount spent on gold products. |
| **NumDealsPurchases** | The number of purchases made with a discount or promotional deal. |
| **NumWebPurchases** | The number of purchases made through the company's website. |
| **NumCatalogPurchases** | The number of purchases made through product catalogs. |
| **NumStorePurchases** | The number of purchases made through physical stores. |
| **NumWebVisitsMonth** | The number of visits to the company's website per month. |
| **AcceptedCmp3** | Binary indicator (1/0) showing whether the customer accepted the third marketing campaign. |
| **AcceptedCmp4** | Binary indicator (1/0) showing whether the customer accepted the fourth marketing campaign. |
| **AcceptedCmp5** | Binary indicator (1/0) showing whether the customer accepted the fifth marketing campaign. |
| **AcceptedCmp1** | Binary indicator (1/0) showing whether the customer accepted the first marketing campaign. |
| **AcceptedCmp2** | Binary indicator (1/0) showing whether the customer accepted the second marketing campaign. |
| **Complain** | Binary indicator (1/0) showing whether the customer has made a complaint. |
| **Z_CostContact** | A constant cost associated with contacting a customer. |
| **Z_Revenue** | A constant revenue associated with a successful campaign response. |
| **Response** | Binary indicator (1/0) showing whether the customer responded to the marketing campaign. |

## New Features Created

The following features were created during feature engineering:

| Feature | Description |
|---|---|
| **Age** | Age of the customer as of 2026. |
| **Total no. of Children** | Total number of children and teenagers in the household, calculated using `Kidhome` and `Teenhome`. |
| **Total Spending** | Total amount spent on wines, fruits, meat, fish, sweets, and gold products. |
| **Customer_Since** | Customer tenure calculated up to **09/09/2026**. |
| **AcceptedCampaigns** | Total number of marketing campaigns accepted, including the current campaign. |
| **AcceptedAny** | Binary indicator (1/0) showing whether the customer accepted at least one marketing campaign. |
| **AgeGroup** | Customers divided into age groups: `18-29`, `30-39`, `40-49`, `50-59`, `60-69`, and `70+`. |