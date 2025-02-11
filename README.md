# <center><font size=8>PERSONAL LOAN CAMPAIGN - MACHINE LEARNING</font></center>

## **Problem Statement**

### **Business Context**

AllLife Bank, a growing US-based bank, aims to expand its asset customer base by converting more liability customers(depositors) into personal loan customers. Although a recent marketing campaign showed a 9% success rate in loan conversions, the bank seeks to improve this rate by leveraging customer data to design better-targeting marketing strategies.

### **Objectives**

AllLife Bank wants to enhance its personal loan conversion rate by leveraging customer data and predictive analytics. The bank aims to identify high-potential customers among its depositors and develop targeted marketing strategies to improve engagement and conversion rates. By analyzing customer demographics, transaction history, and financial behavior, the goal is to build a data-driven model that personalizes marketing efforts, optimizes outreach, and increases the efficiency of loan promotions. Additionally, the bank seeks to minimize acquisition costs, improve customer experience, and ensure sustainable business growth by expanding its asset customer base while managing credit risk effectively.

### **Data Dictionary**

1) **ID:**   Customer ID.

2) **Age:**  Customer's age.

3) **Experience:** Years of professional experience.

4) **Income:** Annual income (in thousand dollars).

5) **ZIPCode:** ZIP Code of the customer's home address.

6) **Family**: Family size.

7) **CCAvg**: Average monthly credit card spending (in thousand dollars).

8) **Education** : Education level (1: Undergrad, 2: Graduate, 3: Advanced/Professional).

9) **Mortgage**: Value of house mortgage (in thousand dollars).

10) **Personal_Loan**: Target variable (1: Accepted the loan, 0: Did not accept).

11) **Securities_Account**: Ownership of a securities account (1: Yes, 0: No).

12) **CD_Account**: Ownership of a certificate of deposit account (1: Yes, 0: No).

13) **Online**: Usage of internet banking (1: Yes, 0: No).

14) **CreditCard**: Ownership of a credit card issued by another bank (1: Yes, 0: No).


1. Total Records : The Dataset Contains 5000 rows and 14 Columns
2. No Missing Data : There are no null values Present. All columns have 5,000 non-null entries.
3. Data Types : 
    * 13 columns with integer data types (int64), including the target variable (Personal_Loan).
    * 1 column with float data type (CCAvg), which represents average monthly credit card spending.
4. Column Insights:
    * ID: A unique identifier for each customer.Not relevant for modeling as it does not provide   predictive information about the target variable.
    * Age, Experience, Income, Family, CCAvg, Mortgage:

        These are numerical features:
        * Age: Customer's age in years.
        * Experience: Professional experience in years.
        * Potential issue: Negative values should be addressed.
        * Income: Annual income in thousand dollars, a likely predictor of loan acceptance.
        * Family: Family size (integer between 1–4).
        * CCAvg: Average credit card spending per month (in thousand dollars), likely indicative of spending habits.
        * Mortgage: Value of house mortgage in thousand dollars; useful for understanding financial commitments.

    * ZIPCode: Represents the customer’s location.
        Likely not predictive for loan acceptance since ZIP codes do not directly influence customer financial behavior.
    * Education:
        Categorical feature (1: Undergrad, 2: Graduate, 3: Advanced/Professional).
        Higher education levels may correlate with higher income and loan acceptance likelihood.

    * Securities_Account, CD_Account, Online, CreditCard:

        * Binary categorical features (1: Yes, 0: No):
            * Ownership of securities or certificate of deposit accounts might indicate financial stability.
            * Online banking usage and credit card ownership may reflect modern financial behavior or spending capacity.

    * Personal_Loan:

        * Target variable (1: Accepted the loan, 0: Did not accept).
        * The objective is to predict this based on customer attributes.



## Decision Tree
![image](https://github.com/user-attachments/assets/11ca9a23-c4da-42e3-bab1-842fd140f83a)

## Decision Tree (Pre-Pruning) 
![image](https://github.com/user-attachments/assets/189249aa-cb0d-487d-8b10-8fa2888014c9)

## Decision Tree (Post - Pruning)
# 
![image](https://github.com/user-attachments/assets/84dbb0ac-4535-4689-a178-9e359c06cd50)

![image](https://github.com/user-attachments/assets/6d1aa0ec-e79b-43f2-bc26-44e47d338cfa)



