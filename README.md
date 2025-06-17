
# 📊 Strategic Churn Intelligence for Telecom Growth                                    

![Facebook vs AdWords](https://spyro-soft.com/wp-content/uploads/2023/07/churn-rate.png)

# Problem Statement
Subscription-based businesses often face significant revenue loss due to customer churn—the rate at which customers cancel their service. Acquiring new customers is usually far more expensive than retaining existing ones, making churn reduction a high-priority business goal. However, without predictive analytics, it is difficult to know which customers are most likely to leave and which actions will be most effective in retaining them.

## 🎯 Project Objectives

 1. **Identify Key Churn Drivers**  
   Analyze customer demographics and behavioral metrics to uncover the most significant factors influencing churn.

 2. **Segment High-Risk Customers**  
   Group customers by churn risk to enable more focused and cost-effective retention strategies.

 3. **Predict Customer Churn**  
   Build a predictive model that assigns churn risk scores to each customer, enabling early intervention.

 4. **Recommend Retention Actions**  
   Translate insights into clear, actionable steps for marketing, product, and support teams to reduce churn.

 5. **Quantify Business Impact**  
   Simulate how reducing churn influences **Customer Lifetime Value (CLV)** and total revenue.


# 🧭 Project Goals

✅ Identify key drivers of customer churn  
✅ Segment customers by behavior and demographics  
✅ Quantify CLV differences between churned and retained users  
✅ Simulate the effect of churn reduction on CLV  
✅ Deliver a business-ready Tableau dashboard with actionable insights  


# 📊 Project Overview
This project analyzes customer churn data for a subscription-based service to identify key risk drivers and simulate retention strategies aimed at improving customer lifetime value (CLV). Two Tableau dashboards are presented:

Dashboard 1: Churn Risk and Segmentation Overview

Dashboard 2: CLV Insights and Retention Strategy Simulation


# 🔗 Tableau Dashboard Link
https://public.tableau.com/app/profile/prabhjot.singh7010/viz/ChurnOptimizationCustomerSegmentDashboard/Story1?publish=yes 



# 📊 Dashboard 1: Churn Risk & Segment Insights

📌 **56%** of customers have churned  
📌 Churn risk is **highest** among:
- Seniors (60+) → 100% churn
- Females → 66% churn
- Monthly contract users → nearly universal churn  
📌 **Support Calls >6** and **Payment Delay >20 days** trigger near-certain churn  
📌 Retained customers have **38% higher CLV** than churned


## 📈 Visuals:

Pie chart: Churn distribution

Bar plots: Age group vs churn, Gender vs churn

Heatmap: Churn across contract types and support calls

Risk segment breakdown (High, Medium, Low)




# 💸 Dashboard 2: CLV Simulation & Retention Strategy Impact

This dashboard visualizes the business impact of reducing churn using simulated strategies calculated in Python.

## 🧪 Retention Strategies (Simulated in Python):
Monthly Contract Fix	Retained 15% of churners with monthly plans	↓ 3.0%

Support Call Fix	Retained 15% with >5 support calls	↓ 3.8%

Payment Delay Fix	Retained 15% with >20 day delay	↓ 2.5%

Senior Fix	Retained 15% of age >51	↓ 2.2%

Final Churn Rate	After all fixes	↓ 45.2%

## 💡 CLV Results

CLV was recalculated after each fix using the formula:

CLV = ARPU / Churn Rate
(ARPU = Total Spend / Tenure)

Metric	Before Fixes (56.7%)	After Fixes (45.2%)

ARPU	$34.01	$34.01

Projected CLV	~$600	~$752

CLV Growth	—	↑ ~25.3%

## 📈 Revenue Impact:
Simulated across 440K customers

Estimated lifetime revenue gain: ~$24 Million


# Recommendation/Loyalty Strategies

## 1.Contract Optimization Program
Problem Identified: Most high-risk churners are on monthly contracts.

**Strategy**:Offer exclusive discounts or rewards to monthly subscribers who upgrade to annual or quarterly plans.
Introduce loyalty points for longer-term commitments.
Goal: Improve retention by increasing contract stickiness.


## 2.Proactive Support Outreach
Problem Identified: Customers with more than 5 support calls are at high risk.

**Strategy**:
Flag customers with rising support frequency.
Assign dedicated customer success agents or provide fast-track issue resolution.
Automate follow-ups after support calls to measure satisfaction.
Goal: Reduce churn due to unresolved frustration or repeated issues.


## 3. On-Time Payment Reminder Program
Problem Identified: Customers with payment delays >20 days have a much higher churn rate.

**Strategy**:Send automated SMS/email reminders before due dates.
Introduce grace periods, auto-pay incentives, or payment flexibility.
Offer small loyalty credits for consistent on-time payers.
Goal: Build trust and reduce churn due to billing friction.


## 4.Senior-Centric Retention Campaign
Problem Identified: Customers aged 51+ show elevated churn risk.

**Strategy**:Launch targeted messaging and simplified interfaces tailored to senior customers.
Offer exclusive senior loyalty benefits or educational support.
Use personal outreach or concierge support services for users 51+.
Goal: Improve confidence and comfort, building long-term loyalty with aging user base.


                                    
## 5 Personalized Engagement Lifecycle
**Strategy**:
Use behavior-triggered communications (e.g., inactivity alerts, usage tips).
Reward long-term usage milestones (e.g., 6 months of continuous use).
Send personalized offers based on churn risk, age, usage frequency.
Goal: Create emotional loyalty and keep customers engaged throughout their journey.


# 📌 Conclusion

This end-to-end churn analytics project:

Identifies key churn drivers

Simulates realistic retention strategies

Demonstrates CLV uplift and revenue growth

Presents insights in executive-ready dashboards

# 👨‍💻 Author

**Prabhjot Singh**  
🎓 B.S. in Information Technology, Marymount University  
🔗 [LinkedIn](https://www.linkedin.com/in/prabhjot-singh-10a88b315/)  
🧠 Passionate about data-driven decision making, analytics, and automation

---

## ⭐ Support

If you found this project useful, feel free to ⭐ it and share it with others!
