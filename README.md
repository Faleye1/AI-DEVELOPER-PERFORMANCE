# AI Developer Performance Analysis (Excel-Based Project)

## 📌 Project Overview
This project investigates the performance of AI developers using **Microsoft Excel** as the primary analytical tool.  
The study applies **correlation analysis, simple regression, and multiple linear regression** to examine how work habits and human factors influence developer productivity and performance outcomes.

---

## 🎯 Research Questions
1. How does AI usage affect developer productivity?
2. Does sleep duration influence task success rate?
3. What is the relationship between stress level and errors?
4. Which factors contribute most to high developer performance?
5. Do longer coding hours improve output quality or performance?

---

## 🧰 Tools Used
- Microsoft Excel  
  - Data Analysis ToolPak  
  - Correlation (CORREL function)  
  - Simple Regression  
  - Multiple Linear Regression  
  - Pivot Tables  
  - Interactive Dashboard (KPIs, Charts, Slicers)
- Power BI (visual reporting)

---

## 📊 Detailed Analysis and Results

---

### **Question 1: How does AI usage affect developer productivity?**
**Method:** Simple Linear Regression  
- Dependent Variable: Productivity Score  
- Independent Variable: AI Usage Hours  

**Key Results:**
- Multiple R = **0.4381**
- R² = **0.1919**
- F-statistic = **237.05**
- Significance F = **3.75E-48**
- Coefficient for AI Usage Hours = **7.89** (p < 0.001)

**Interpretation:**  
AI usage has a **statistically significant positive effect** on developer productivity. Approximately **19% of the variation in productivity** is explained by AI usage hours, indicating that increased use of AI tools improves productivity, though other factors also contribute.

---

### **Question 2: Does sleep duration influence task success rate?**
**Method:** Pearson Correlation Analysis  

**Result:**
- Correlation coefficient (r) = **0.0546**

**Interpretation:**  
The correlation between sleep duration and task success rate is **very weak and positive**, suggesting that sleep hours have **little to no linear influence** on task success rate among developers in this dataset.

---

### **Question 3: What is the relationship between stress level and errors?**
**Method:** Pearson Correlation Analysis  

**Result:**
- Correlation coefficient (r) = **−0.0345**

**Interpretation:**  
There is a **very weak negative relationship** between stress level and errors, indicating that stress level does not have a significant linear relationship with the number of errors made by developers.

---

### **Question 4: Which factors contribute most to high performance?**
**Method:** Multiple Linear Regression  

**Independent Variables:**
- AI Usage Hours  
- Hours of Coding  
- Sleep Hours  
- Stress Level  

**Model Performance:**
- Multiple R = **0.8495**
- R² = **0.7216**
- Adjusted R² = **0.7099**
- F-statistic = **61.57**
- Significance F = **1.47E-25**

**Significant Predictors:**
- Hours of Coding (β = **49.49**, p < 0.001)
- AI Usage Hours (β = **22.45**, p < 0.001)

**Interpretation:**  
Developer performance is strongly influenced by **hours of coding and AI usage**. Sleep hours and stress level do not significantly predict performance in the presence of other variables.

---

### **Question 5: Do longer coding hours improve output quality or performance?**
**Method:** Simple Linear Regression  

**Results:**
- R² = **0.000002**
- Coefficient for Hours of Coding = **−0.0097**
- p-value = **0.988**

**Interpretation:**  
There is **no statistically significant relationship** between coding hours and output quality when considered independently. This suggests that **coding duration alone does not improve performance** without considering other factors.

---

## 📈 Dashboard Features
- KPI metrics (Average Productivity, Task Success Rate, Errors)
- Regression and correlation visual summaries
- Pivot-based charts
- Interactive slicers for dynamic filtering
- Clean layout optimized for insight communication

---

## 📁 Project Files
- Excel Analysis Workbook (`.xlsx`)
- Power BI Dashboard (`.pbix`)

---

## 🧾 Conclusion
This project demonstrates that while **AI usage and active coding time significantly improve developer performance**, factors such as sleep duration and stress level show minimal linear impact. The results highlight the importance of **tool usage efficiency and focused work habits** over sheer time investment.

---

## 👤 Author
**Faleye Taiwo Elijah**

---

## 📄 License
This project is for academic and learning purposes only.

