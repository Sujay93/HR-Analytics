# HR-Analytics

## Page 1
![Page 1](https://github.com/user-attachments/assets/a4c97fde-7eb7-4f03-b361-23c9380e5f14)

## Page 2
![Page 2](https://github.com/user-attachments/assets/43fcc82b-86c3-4f90-ba1b-5191740ec4cd)

## Business Problem
* The company has recently observed an unusually high number of employees leaving the organization, leading to growing concern among        senior leadership. Despite offering industry-standard salaries and training programs, attrition has climbed above 50%, affecting          critical departments such as Research & Development and Human Resources.
* Management is perplexed by the rising turnover and lacks clarity on the underlying causes. To address this, the HR department has         initiated a comprehensive data analysis aimed at uncovering the key factors driving attrition — such as work-life balance, job            satisfaction, commute distance, and departmental dynamics — with the ultimate goal of improving employee retention and organizational     stability.

## Business Questions
1. **Which departments have the highest and lowest attrition rates?**
2. **How does job satisfaction vary across different departments?**
3. **What is the relationship between overtime and employee performance?**
4. **Does the distance from home correlate with higher attrition?**
5. **Which job roles exhibit the lowest work-life balance ratings?**
6. **How does average tenure differ across departments?**
7. **Is there a link between training time and performance rating?**
8. **How does salary hike influence job satisfaction?**
9. **What is the age distribution across departments, and could it impact attrition?**

---
## Insights

1. **High Attrition in R&D and HR Departments**: R&D shows the highest attrition rate (51.21%), followed by the HR department,              indicating potential department-specific issues.

2. **Frequent Overtime Linked to Lower Performance:** Employees working overtime consistently show lower average performance ratings,       suggesting burnout or overwork.

3. **Attrition Increases with Commute Distance:** A clear upward trend is observed between distance from home and attrition, especially     beyond 10–15 km.

4. **Job Roles like Sales Executive Have Poor Work-Life Balance:** Certain job roles report significantly lower work-life balance          scores, especially Sales-related functions.

5. **Higher Training Hours Show Slight Performance Gains:** Employees with more training hours generally perform better, though the         impact varies by department.

6. **Salary Hikes Don’t Guarantee Satisfaction:** While salary hikes do boost satisfaction to a degree, some employees with good hikes      still report dissatisfaction.

7. **Unequal Distribution of Stock Options:** Stock options are disproportionately allocated, which may contribute to perceived             inequality across departments.

## Recommendations

1. **Address Attrition in R&D and HR:** Conduct exit interviews and departmental audits to understand pain points and improve retention     strategies.

2. **Control Overtime and Promote Work-Life Balance:** Enforce limits on overtime and provide resources to reduce workload pressure,        especially in underperforming teams.

3. **Offer Flexible or Hybrid Work Options:** Reduce commute-related attrition by offering remote work flexibility or transport             incentives.

4. **Reassess Job Role Expectations:** For roles with poor work-life balance, revise performance targets or redistribute                    responsibilities.

5. **Increase Investment in Targeted Training Programs:** Focus training on departments or roles with lower performance to improve          outcomes and motivation.

6. **Enhance Retention Beyond Compensation:** Along with salary hikes, improve recognition programs, internal mobility, and employee        engagement initiatives.

7. **Ensure Fair and Transparent Incentive Structures:**
   Align stock option and benefit distribution with performance and department needs to improve morale.

---

## Dataset
* The dataset was sourced from two separate CSV files HR_1 and HR_2 containing employee and HR-related information.
* Both files were imported and merged using Power BI's Power Query Editor to create a unified dataset for analysis.
* The link to both the datasets is mentioned below:
  - For HR_1.csv - [https://github.com/Sujay93/HR-Analytics/blob/main/HR_1.csv]
  - For HR_2.csv - [https://github.com/Sujay93/HR-Analytics/blob/main/HR_2.csv]

## Data cleaning
* Removing null or duplicate entries.
* Standardizing column formats and renaming headers for clarity.
* Creating calculated columns and transforming data types as required for analysis.

## Data Visualization and Analysis
1. **Department wise Attrition Rate**
   ![Dept wise attrition rate](https://github.com/user-attachments/assets/497592b4-7bf9-4c94-8f53-a76606e6d14a)
  
* **Research & Development** shows the highest attrition rate at **31.14%**, indicating possible issues like workload pressure or low      engagement.
* **Sales** has the lowest attrition rate at **15.71%**, suggesting higher job satisfaction or effective retention strategies.
* **Human Resources (20.33%), Software (23.93%), and Support (20.11%)** reflect moderate attrition, warranting deeper analysis.
* Attrition rates vary widely across departments, with R&D showing a sharp spike compared to others.
* Departments with lower attrition, like Sales, may offer best practices that can be applied to high-attrition teams.

2. **Overtime vs Performance Rating**
   ![Over Time vs Performance Rating](https://github.com/user-attachments/assets/2911d602-df3b-4d8a-8f35-ddb5161a2d5c)

* Employees without overtime across all departments show similar average performance ratings (~2.49 to 2.51).
* In the **Sales department**, overtime correlates with a drop in performance rating (from 2.49 to 2.46), suggesting burnout or overload.
* **Support and Software departments** show a slight improvement in performance when overtime is involved, with Support peaking at 2.52.
* Departments like **Hardware and HR** exhibit minimal impact from overtime on performance.
* The effect of overtime on performance is department-specific, indicating a need for tailored workload and resource management.

3. **Attrition vs Distance from Home**
   ![Attrition vs Distance from home](https://github.com/user-attachments/assets/ba8f0c21-d980-48d8-b34b-2114b64767b8)

* Attrition count fluctuates significantly across different commute distances, showing a non-linear trend.
* **Higher attrition peaks** are observed around distances of **10 km (525), 20 km (547), 30 km (540), and 50 km (539)**.
* **Lowest attrition** occurs around the **40 km mark (463)**, indicating an unexpected dip.
* These patterns suggest a potential correlation between longer or inconsistent travel distances and higher attrition.
* Commute-related stress or inconvenience could be a contributing factor to employee turnover.

4. **Job Role wise Average work-life balance**
   ![Job Role wise Avg Work Life balance](https://github.com/user-attachments/assets/d4c909f3-3b7e-4b21-ab71-830cc99e4810)

* **Research Scientists** report the **highest average work-life balance** score at 2.514, indicating better work-life satisfaction.
* **Sales Executives** have the **lowest score at 2.469**, pointing to greater work-life imbalance.
* There’s a **gradual decline in work-life balance** from technical/research roles toward sales-oriented roles.
* This suggests a need for role-specific interventions to improve employee satisfaction and retention.

5. **Training Time vs Performance Rating**
   ![Training time vs Performance rating](https://github.com/user-attachments/assets/5b6d2c06-1a72-4201-8c35-c4e1f577b2c7)

* Training hours range from 1 to 6, with performance ratings clustering tightly **between 2.46 and 2.52**.
* A **slight upward trend** is visible—employees with more training tend to have slightly higher performance ratings.
* The **highest average performance (~2.52)** is seen at the **6-hour training mark**.
* While the impact is marginal, the data suggests that training investments may contribute positively to employee performance.

6. **Salary Hike vs Job Satisfaction**
   ![Salary hike vs Job satisfaction](https://github.com/user-attachments/assets/9710cf6f-4652-45a8-b574-f31215908c22)

* There is no consistent linear relationship between job satisfaction and percent salary hike—employee responses vary widely.
* Peaks in satisfaction (~3.89) occur around certain salary hikes (e.g., ~20%), suggesting limited but impactful correlations.
* **Low satisfaction levels (~2.0–2.5**) appear across multiple salary hike values, indicating that compensation increases alone don’t    guarantee satisfaction.
* The fluctuating trend implies that other factors—such as work culture, recognition, or leadership—influence job satisfaction more        strongly than salary changes.

## Conclusion

* This HR analytics project aimed to uncover key factors contributing to high employee attrition within the organization. Through          detailed analysis of various employee attributes—such as department, overtime, distance from home, training time, job satisfaction,      and salary hikes—the dashboard provides actionable insights into workforce behavior and engagement.
* The findings highlight that attrition is influenced by a combination of factors, not just compensation. Areas such as overtime impact,   work-life balance, and departmental dynamics play a significant role in employee satisfaction and retention.
* These insights can help HR teams and management develop targeted strategies to improve employee retention, optimize engagement, and      create a more supportive and productive work environment.




