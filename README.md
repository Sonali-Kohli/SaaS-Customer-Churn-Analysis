# SaaS-Customer-Churn-Analysis

Power BI | Excel

Objective:
•	The Company: "**FitFlex App**", a fast-growing, mid-stage B2C fitness software startup that offers monthly and annual app subscriptions.
•	The Problem: The Executive Team noticed that while new user acquisition is highly successful, the **revenue is flattening** because of an accelerating customer churn rate.
•	The Goal: Build an interactive **Power BI dashboard** to identify who is churning, when they leave, why they are leaving, and provide **three data-backed recommendations to improve user retention**

<img width="3780" height="1073" alt="dashboard" src="https://github.com/user-attachments/assets/deab20b9-7582-42a3-8450-ddbf9bd71285" />

## **Core metrics and KPIs:**
Base churn rate – 26.54%
Lost Revenue (MRR) - $139K
Total active customers – 7.043K at beginning, 5.174K in the end
Biggest driver – Overpriced or bad deal
Most affected segment – Premium and UPI users
By pricing plan – 88% churned were on month-to-month basis plan
By payment method – 77% among those who churned in the first month itself were using UPI

## **Business Questions:**
### **Page 1: Executive Insights (The "What")** 
•	KPI Cards: Total Customers, Active Users, Churn Rate (%), and Monthly Recurring Revenue (MRR) Lost.
•	Donut Chart: Churn breakdown by Contract Type (Month-to-month vs. One-year vs. Two-year).
•	Line Chart: Churn trends mapped over time to see if the problem is worsening.  
### **Page 2: Customer Behavioral Drill-Down (The "Who & Why")** 
•	Clustered Bar Chart: Churn rate vs. Tenure Months (e.g., Do users drop off in Month 1, or Month 6?).
•	Matrix Table: Churn rate segmented by Payment Method (e.g., Credit Card vs. Electronic Check) to spot involuntary churn caused by expired cards.
•	Slicers: Filter options for AppTier, Gender, and Tech Support Tickets Opened.  
### **Page 3: Predictive Risk Matrix (The Action Plan)**
•	Scatter Plot: Average Monthly Charges vs. Tenure, color-coded by Churn Status.
•	Table List: A filtered list of "At-Risk Customers" (e.g., users on month-to-month plans, paying with electronic checks, who have open support tickets) to target for retention campaigns. 

## **Key Insights:**
1. Highest churn rate is in the 1st month i.e. 61.99%. A high churn rate in the 1st month indicates poor customer onboarding or a mismatch between marketing and the actual product.
2. More than 88% churned were buying month-to-month subscription plans. Around 77% among those who churned in the first month itself were using UPI. And around 42% churned customers had a premium plan. This suggests a huge gap between the offer and the real quality or usability of the product for the target.
3. For premium members, who churned, all of them had allowed notification reminders, most of them had services like live workout classes and diet plan. Therefore, there was initial engagement with the platform and an expectation of certain outcome, i.e. becoming healthy, most probably by building a habit or routine with the help of the app.

## **Recommendations:**
4 customers segments were derived based on the analysis and following were the recommendations:

Term	      | Priority	| Segment	      | Recommendation
:---------  | :-------- | :-----------  | :-------------
Always	    | High	    | All	          | Mandatory 3-part email sequence
Immediately	| High	    | Priority	    | Product improvement through better services
Short-term	| Medium	  | Important	    | 21-day free premium plan
Long-term	  |  Low	    | Nice to have	| Increase community level engagements

