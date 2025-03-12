# **Credit Card Spending & Customer Behavior Analysis**

## **1. Relationship Between Customer Behavior and FICO Score**

### **a. Do Customers with Higher FICO Scores Spend More?**
- **Insight:** Customers with higher FICO scores do not spend more on average. In fact, customers with the lowest FICO scores have the highest average spending.  
- **Possible Explanation:** Lower FICO score customers may rely more on credit for everyday expenses or large purchases, whereas higher FICO score individuals may manage their credit more conservatively.  
- **Actionable Insight:** Financial institutions should analyze spending patterns of low-FICO customers to assess potential risks of financial distress. Personalized credit limit adjustments and spending management tools could help maintain financial stability for low-FICO customers.

---

### **b. Relationship Between FICO and Transaction Errors (Insufficient Balance)**
- **Insight:** Higher FICO scores are expected to correlate with fewer "Insufficient Balance" errors. If low-FICO customers experience more failed transactions, it may indicate financial instability.  
- **Actionable Insight:** Proactive offerings like overdraft protection, spending alerts, or budgeting tools could help customers facing insufficient balance errors. Credit risk models can be enhanced by including real-time transaction failure trends for improved lending decisions.

---

### **d. State-Level Spending Insights**
| **State**           | **Avg Monthly Spend Per Customer** | **Number of Customers** |
|---------------------|-----------------------------------|-------------------------|
| **California**      | $845,714.98                        | 238                     |
| **Texas**           | $589,011.45                        | 157                     |
| **New York**        | $503,381.74                        | 124                     |
| **Florida**         | $425,517.49                        | 130                     |
| **Pennsylvania**    | $285,760.82                        | 83                      |


- **Insight:** California leads in average monthly spending per customer, with nearly 1.5x the spend of Texas, the second-highest state. Spending levels do not correlate directly with population size (e.g., Florida has more customers but lower average spend than New York).  
- **Actionable Insight:** The bank should target **state-specific credit card promotions** based on regional spending behaviors. Higher-spending states can be prioritized for **premium credit card offers**, while moderate-spending states may benefit from **cashback or installment plan options**.

---

### **e. Relationship Between Income and Monthly Spending**
- **Insight:** There is little correlation between yearly income and monthly spending, even when segmented by age group.  
- **Possible Explanation:** Spending may be driven by lifestyle choices rather than income levels. High-income individuals might prefer using alternative payment methods (e.g., bank transfers or investment accounts) instead of credit cards.  
- **Actionable Insight:** The bank should shift focus from income-based segmentation to analyzing **spending categories** (e.g., luxury vs. essential purchases) to offer more tailored credit card benefits.

---

## **2. Credit Card Transaction Trends**

### **a. Transaction Method Preferences**
| **Transaction Type**   | **Total Spending (in currency units)** |
|------------------------|----------------------------------------|
| **Chip Transactions**  | 236,385,920.15                         |
| **Online Transactions**| 50,986,086.80                          |
| **Swipe Transactions** | 57,329,102.52                          |

- **Insight:** **Chip transactions dominate**, accounting for the majority of total spending, while **online** and **swipe transactions** contribute significantly less.  
- **Actionable Insight:** Since **chip transactions** are the preferred method, the bank should focus on optimizing customer experience at physical POS (Point-of-Sale) terminals. For **online transactions**, which have a relatively lower spend, offering **incentives** like **cashback or promotional discounts** could drive higher engagement.

---

### **b. Online Spending Trends**
- **Insight:** Online spending remains stable over time, with a noticeable spike in the 10s and 20s age groups towards the end of 2019.  
- **Actionable Insight:** The **spike in online spending** among younger customers could be linked to broader **e-commerce trends** or seasonal factors. Offering **specialized online rewards**, partnerships with e-commerce platforms, or **Buy Now, Pay Later (BNPL) options** could capitalize on this growing trend.

---

### **c. Overall Spending Stability & Late-2019 Decline**
- **Insight:** Most age groups have maintained steady spending rates across the five years, with a slight decline in spending observed towards the end of 2019.  
- **Actionable Insight:** The reasons behind the **late-2019 decline** need to be explored further—whether due to **economic conditions, regulatory changes, or shifts in consumer behavior**. Targeted **promotions in Q4** can help mitigate potential future slowdowns in spending.

---

## **Next Steps for Deeper Analysis**

1. **Analyze Transaction Frequency and FICO Scores**
   - Do high-FICO customers transact more frequently or make fewer but higher-value transactions?  
   - How does transaction frequency correlate with credit utilization rates?

2. **Investigate Insufficient Balance Errors**
   - Are low-FICO customers experiencing repeated transaction failures?  
   - What interventions can be put in place to reduce financial distress?

3. **Explore Spending Patterns by Merchant Category**
   - Do high-FICO vs. low-FICO customers spend differently on categories like travel, luxury goods, or groceries?  
   - What categories offer stable spending across income groups, and how can these be further incentivized?
