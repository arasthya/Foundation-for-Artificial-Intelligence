# Foundation for Artificial Intelligence  
Team Assignment at Startup Campus

### Case 1: Withdraw All Savings in Cash

In Indonesia, currency denominations are divided as follows:

**Paper Money**:  
Rp 100,000, Rp 50,000, Rp 20,000, Rp 10,000, Rp 5,000, Rp 2,000  

**Coins**:  
Rp 1,000, Rp 500, Rp 200, Rp 100  

> *Note: Assume all Rp 1,000 denominations are considered as coins.*

In certain situations, a bank may need to disburse the full savings of a customer in cash upon request. This task requires calculating the number of each currency denomination required to fulfill the requested amount.

### Requirements
1. **Prioritize Large Denominations**: Disburse the largest denominations first.
2. **Inform of Any Remaining Balance**: If the balance can't be fully disbursed, show the remaining amount.
3. **Calculate Total Currency Types**: Output the total number of paper money and coins needed.
4. **Maximum Disbursement Limit**: The maximum amount to be disbursed is capped at Rp 1,000,000,000.

### Code Task
Write a Python program that:
- Receives an integer amount (from 0 to 1 billion Rupiah).
- Outputs the number of each denomination needed to match the requested amount.
- Handles invalid inputs or requests exceeding the maximum limit with appropriate messages.

#### Example Scenarios
```plaintext
Input:
>> 2000000000
Output:
>> Maximum Saving is 1000000000

Input:
>> -100
Output:
>> Please input the correct number

Input:
>> 1245123
Output:
>> Amount of currency Rp 100,000: 12  
>> Amount of currency Rp 50,000: 0  
>> Amount of currency Rp 20,000: 2  
>> Amount of currency Rp 10,000: 0  
>> Amount of currency Rp 5,000: 1  
>> Amount of currency Rp 2,000: 0  
>> Amount of currency Rp 1,000: 0  
>> Amount of currency Rp 500: 0  
>> Amount of currency Rp 200: 0  
>> Amount of currency Rp 100: 1  
>>  
>> Total Paper Money: 15  
>> Total Coins: 1  
>> Cannot be cashed out: 23
```

---

### Case 2: HR Analytics and Data Visualization

### Overview
This case involves the use of an HR dataset to build data analytics and visualization models, supporting insights in human resources management. The dataset was created to aid HR professionals in improving analytical skills.

### Dataset
- **Source**: [HRDataset_v14.csv](https://raw.githubusercontent.com/Rietaros/kampus_merdeka/main/HRDataset_v14.csv)
- **Content**: The dataset includes various HR metrics used to evaluate employee demographics, job roles, performance, and other critical HR factors.

### Objectives
1. **Data Exploration and Cleaning**: Perform preprocessing steps to prepare the data for analysis.
2. **Data Visualization**: Create visualizations to reveal insights on employee performance, retention, and job satisfaction.
3. **Predictive Modeling**: Develop prediction models to analyze patterns and trends within HR data, providing actionable insights for decision-making.

### Analysis & Modeling Tools
- **Python Libraries**: Use libraries such as pandas, numpy, matplotlib, seaborn, and scikit-learn for data handling, visualization, and modeling.

---
