# Ecomerce churn analysis
# :books: Table of Contents <!-- omit in toc -->

- [:briefcase: Dataset and Requirement](#dataset-and-requirement)
- [:bookmark_tabs: Example Data](#bookmark_tabsexample-data)
- [🔎 Explore data and test model](#--explore-data-and-test-model)

---

# Dataset and Requirement
The data set belongs to a leading online E-Commerce company, contains information of 5630 customers. It shows personal information, purchasing habits, feedback,... and whether the customer has churned or not.

### ❓ Question
Can you predict whether customers will churn based on customer data ?

---
# :bookmark_tabs:Example Data

<details><summary> 👆🏼 Data information </summary>

Data has 20 columns and 5630 rows:
- CustomerID: Unique customer ID
- Churn: Churn Flag (1 is churned, 0 is not churned)
- Tenure: Tenure of customer in organization
- CityTier: City Tier
- PreferredLoginDevice: Preferred login device of customer
- WarehouseToHome: Distance in between warehdwouse to home of customer
- PreferredPaymentMode: Preferred payment method of customer
- Gender: Gender of customer
- HourSpendOnApp: Number of hours spend on mobile application or website
- NumberOfDeviceRegistered: Total number of devices is registered on particular customer
- PreferedOrderCat: Preferred order category of customer in last month
- SatisfactionScore: Satisfactory score of customer on service
- MaritalStatus: Marital status of customer
- NumberOfAddress: Total number of added added on particular customer
- Complain: Any complaint has been raised in last month
- OrderAmountHikeFromlastYear: Percentage increases in order from last year
- CouponUsed: Total number of coupon has been used in last month
- OrderCount: Total number of orders has been places in last month
- DaySinceLastOrder: Day Since last order by customer
- CashbackAmount: Average cashback in last month

</details>


<details><summary> 👆🏼 Data sample rows </summary>

<div align="center">
	
**Table** 

<div align="center">
	
First 5 rows
	
| CustomerID | Churn |	Tenure |	PreferredLoginDevice |	CityTier |	WarehouseToHome|	PreferredPaymentMode |	Gender |	HourSpendOnApp |	NumberOfDeviceRegistered |	PreferedOrderCat |	 SatisfactionScore |	MaritalStatus |	NumberOfAddress |	Complain |	OrderAmountHikeFromlastYear |	CouponUsed |	OrderCount |	DaySinceLastOrder |	CashbackAmount |
|-----------|------|-------|---------------------|---------|---------------|---------------------|-------|---------------|-------------------------|-----------------|-------------------|--------------|----------------|---------|----------------------------|-----------|-----------|------------------|---------------|
| 50001 |	1 |	4.0 |	Mobile Phone |	3 |	6.0 |	Debit Card |	Female |	3.0 |	3 |	Laptop & Accessory |	2 |	Single |	9 |	1 |	11.0 |	1.0 |	1.0 |	5.0 |	159.93 |
| 50002 |	1 |	NaN|	Phone |	1 |	8.0 |	UPI |	Male |	3.0 |	4 |	Mobile |	3 |	Single |	7 |	1 |	15.0 |	0.0 |	1.0 |	0.0 |	120.90 |
| 50003 |	1 |	NaN |	Phone |	1 |	30.0 |	Debit Card |	Male |	2.0 |	4 |	Mobile |	3 |	Single |	6 |	1 |	14.0 |	0.0 |	1.0 |	3.0 |	120.28 |
| 50004 |	1 |	0.0 |	Phone |	3 |	15.0 |	Debit Card |	Male |	2.0 |	4 |	Laptop & Accessory |	5 |	Single |	8 |	0 |	23.0 |	0.0 |	1.0 |	3.0 |	134.07 |
| 50005 |	1 |	0.0 |	Phone |	1 |	12.0 |	CC |	Male |	NaN |	3 |	Mobile |	5 |	Single |	3 |	0 |	11.0 |	1.0 |	1.0 |	3.0 |	129.60 |

</details>  

---

## 🔎  Explore data and test model

### The Process is following 
- [Data Cleaning](https://colab.research.google.com/drive/1PXCQowsZyXC2Bils2oN7AinVXEVUiuLh?hl=vi#scrollTo=vwCzS7dXvYbp)
- [EDA](https://colab.research.google.com/drive/1vncWaAklJbFMJ3jUAD7oRCwkC9yFCu4v?hl=vi#scrollTo=3UUbOme8WS15) 
- [Data preprocessing and modeling](https://colab.research.google.com/drive/1nHdTfJ8_vRWfNTWsx1_foZQxB4ia8yn3?hl=vi)
