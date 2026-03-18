# AtliQO Bank: Credit Card Launch Analysis and A/B Testing

### **The Story: Finding the Diamond in the Rough**
AtliQO Bank had a massive dataset but a simple problem: They didn't know which customer segment to target for their new credit card. As a Data Scientist, my mission was to act like a detective, clean the messy data, find a hidden market opportunity, and prove its success using pure mathematics.

---

### **Phase 1: The Detective Work (Data Cleaning)**
The raw data was full of noise and errors that could lead to wrong business decisions. I started by sanitizing the environment:
* **Age Filtering:** I restricted the analysis to a valid working-class age group between **18 and 64 years**.
* **Fixing System Glitches:** I discovered over **4,700 transactions** with a zero value, specifically in the Electronics category. Instead of deleting them, I logically replaced them with the **Median** value of similar transactions to keep the data volume intact.
* **Outlier Treatment:** Using the Interquartile Range (**IQR**) method, I identified extreme spending values (some as high as 70k) that were unrealistic and handled them to ensure they didn't skew the final report.

---

### **Phase 2: The "Aha!" Moment (Key Discovery)**
After the data was clean, the patterns started to emerge. While looking at the charts, I found an **Untapped Market**:
* **The 18-25 Segment:** This young group makes up **26%** of the entire customer base.
* **The Spending Gap:** They are the biggest spenders in **Electronics, Fashion, and Beauty**, yet they had the lowest credit card penetration in the entire bank. 
* **The Strategy:** I recommended that the bank stop ignoring this segment and launch a trial credit card specifically for them.

---

### **Phase 3: The Scientific Experiment (A/B Testing)**
To minimize financial risk, I designed a controlled experiment:
1. **Control Group:** 40 customers who continued using their regular payment methods.
2. **Test Group:** 40 customers who were given the new **Trial Credit Card**.
* **The Result:** The campaign saw a **40% conversion rate**, proving that young customers were eager to use the new product.

---

### **Phase 4: The Final Verdict (Statistical Validation)**
A feeling isn't enough in banking; we need proof. I performed a **Two-Sample Z-Test** to compare the spending of both groups:
* **Z-Statistic:** 2.76
* **Critical Value:** 1.64
* **P-Value:** 0.0
* **Decision:** Since the Z-score (**2.76**) is much higher than the Critical Value (**1.64**), we **Reject the Null Hypothesis**. This mathematically proves that the new credit card caused a significant increase in spending.

---

### **Final Conclusion and Recommendation**
The data speaks for itself. Targeting the **18-25 age group** isn't just a good idea—it’s a scientifically proven growth engine for AtliQO Bank. I have recommended a full-scale launch of this card to capture this high-potential market.

---

### **Tech Stack & Methodology**
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Statsmodels
* **Skills:** Data Cleaning, EDA, Hypothesis Testing, A/B Testing, Business Intelligence
