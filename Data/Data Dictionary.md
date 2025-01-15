
---

### **Data Dictionary**

| **Column Name**                  | **Data Type** | **Description**                                                                 | **Notes**                                                                 |
|----------------------------------|---------------|---------------------------------------------------------------------------------|---------------------------------------------------------------------------|
| **Customer ID**                  | Text          | Unique identifier for each customer.                                            | Primary key for the dataset.                                              |
| **Churn Label**                  | Boolean       | Indicates whether the customer has churned (Yes/No).                            | Target variable for churn analysis.                                       |
| **Account Length (in months)**   | Numeric       | Duration of the customer’s account in months.                                   | Helps analyze customer tenure.                                            |
| **Local Calls**                  | Numeric       | Number of local calls made by the customer.                                     | Useful for understanding usage patterns.                                  |
| **Local Mins**                   | Numeric       | Total minutes spent on local calls by the customer.                             | Helps analyze call behavior.                                              |
| **Intl Calls**                   | Numeric       | Number of international calls made by the customer.                             | Indicates international usage.                                            |
| **Intl Mins**                    | Numeric       | Total minutes spent on international calls by the customer.                     | Helps analyze international call behavior.                                |
| **Intl Active**                  | Boolean       | Indicates if the customer has an active international plan (Yes/No).            | Useful for segmentation.                                                  |
| **Intl Plan**                    | Boolean       | Indicates if the customer has an international plan (Yes/No).                   | Helps analyze international plan adoption.                                |
| **Extra International Charges**  | Numeric       | Additional charges incurred for international usage.                            | Indicates potential dissatisfaction.                                      |
| **Customer Service Calls**       | Numeric       | Number of calls made to customer service by the customer.                       | High numbers may indicate dissatisfaction.                                |
| **Avg Monthly GB Download**      | Numeric       | Average monthly data usage in gigabytes.                                        | Helps analyze data consumption patterns.                                  |
| **Unlimited Data Plan**          | Boolean       | Indicates if the customer has an unlimited data plan (Yes/No).                  | Useful for segmentation.                                                  |
| **Extra Data Charges**           | Numeric       | Additional charges incurred for exceeding data limits.                          | Indicates potential dissatisfaction.                                      |
| **State**                        | Text          | The state where the customer resides.                                           | Useful for geographic analysis.                                           |
| **Phone Number**                 | Text          | Customer’s phone number.                                                        | Unique identifier but not used for analysis.                              |
| **Gender**                       | Text          | Gender of the customer (Male/Female).                                           | Useful for demographic analysis.                                          |
| **Age**                          | Numeric       | Age of the customer.                                                            | Helps analyze age-related trends.                                         |
| **Under 30**                     | Boolean       | Indicates if the customer is under 30 years old (Yes/No).                       | Useful for segmentation.                                                  |
| **Senior**                       | Boolean       | Indicates if the customer is a senior (typically 65+ years old) (Yes/No).       | Useful for segmentation.                                                  |
| **Group**                        | Boolean       | Indicates if the customer is part of a group plan (Yes/No).                     | Useful for segmentation.                                                  |
| **Number of Customers in Group** | Numeric       | Number of customers in the group plan (if applicable).                          | Helps analyze group plan usage.                                           |
| **Device Protection & Online Backup** | Boolean | Indicates if the customer has device protection or online backup (Yes/No).      | Useful for segmentation.                                                  |
| **Contract Type**                | Text          | Type of contract (e.g., Month-to-Month, One Year, Two Year).                    | Helps analyze contract-related trends.                                    |
| **Payment Method**               | Text          | Method of payment (e.g., Direct Debit, Paper Check, Credit Card).               | Useful for analyzing payment preferences.                                 |
| **Monthly Charge**               | Numeric       | Monthly charge for the customer’s plan.                                         | Helps analyze revenue and pricing.                                        |
| **Total Charges**                | Numeric       | Total charges incurred by the customer over their account lifetime.             | Useful for analyzing customer lifetime value.                             |
| **Churn Category**               | Text          | Category of churn (e.g., Competitor, Dissatisfaction, Price, etc.).             | Provides reasons for churn (if available).                                |
| **Churn Reason**                 | Text          | Specific reason for churn (e.g., “Moved to a competitor,” “Poor service”).      | Provides detailed insights into churn causes.                             |

---

### **Key Notes:**
1. **Churn Analysis Focus:** The `Churn Label`, `Churn Category`, and `Churn Reason` columns are critical for understanding why customers leave.
2. **Behavioral Insights:** Columns like `Local Calls`, `Intl Calls`, `Avg Monthly GB Download`, and `Customer Service Calls` help analyze customer behavior.
3. **Demographic Insights:** Columns like `Age`, `Gender`, `Under 30`, and `Senior` provide demographic context.
4. **Geographic Insights:** The `State` column allows for regional analysis of churn rates.
5. **Monetization Insights:** Columns like `Monthly Charge`, `Total Charges`, and `Extra Data Charges` help analyze revenue and cost-related factors.

---

