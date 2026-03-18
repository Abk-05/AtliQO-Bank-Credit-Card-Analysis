# AtliQO Bank: Credit Card Launch Analysis and A/B Testing

### **Project Overview**
AtliQO Bank aims to expand its market share by launching a new credit card. The objective of this project was to analyze customer demographics and spending patterns to identify a high-potential **"Untapped Market"** and validate the launch strategy using statistical methods.

---

### **Phase 1: Data Cleaning and Preparation**
The raw data contained several inconsistencies that required careful handling before analysis:

* **Age Filtering:** Restructured the dataset to include only valid age groups between **18 and 64 years**

* **Handling Invalid Transactions:** Identified over **4,700 transactions** with a zero value in the Electronics category. These were corrected using the **median** value of similar transactions

* **Outlier Treatment:** Applied the **Interquartile Range (IQR)** method to handle extreme spending values and prevent skewed analysis

---

### **Phase 2: Key Insights and Market Opportunity**

After cleaning the data, important patterns emerged:

* The **18–25 age group** represents approximately **26 percent** of the total customer base

* This segment shows high spending in:
  * Electronics
  * Fashion
  * Beauty

* However, this group has the **lowest credit card penetration** within the bank

**Strategy:** A targeted credit card offering was proposed specifically for the **18–25 segment**

---

### **Phase 3: A/B Testing Strategy**

To evaluate the effectiveness of the new credit card, a controlled experiment was designed:

* **Control Group (40 customers):** Continued using existing payment methods

* **Test Group (40 customers):** Provided with the new trial credit card

**Result:** The experiment resulted in a **40 percent conversion rate**, indicating strong customer interest

---

### **Phase 4: Statistical Validation**

A **Two-Sample Z-Test** was conducted:

* **Z-Statistic:** 2.76
* **Critical Value:** 1.64
* **P-Value:** 0.0

**Decision:** Since the Z-Statistic is greater than the Critical Value, the null hypothesis is rejected. This confirms that the new credit card significantly increased customer spending

---

### **Final Conclusion**

The analysis demonstrates that the **18–25 age group** is a high-potential segment. Targeting this segment is both a strategic and statistically validated decision

A full-scale launch of the credit card is recommended

---

### **Tech Stack and Methodology**

**Language**
* Python

**Libraries**
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Statsmodels

**Skills**
* Data Cleaning
* Exploratory Data Analysis
* Hypothesis Testing
* A/B Testing
* Business Intelligence
