# Telecom_Analysis_PowerBI

🔍 Overview
AtliQo, one of India’s leading telecom providers, rolled out its 5G plans in May 2022. But since the launch, there’s been a decline in active users and revenue growth. The business director requested an in-depth comparison of KPIs before and after the 5G launch to help recover user rates and optimize internet plans. 💡

🎯 Project Goals

📑 Create an Advanced Report: Reimagine the business user’s mock-up into a clear, insightful, and professional dashboard for top-level management.
🧑‍💼 Executive-Friendly Dashboard: The dashboard must be easy-to-understand and self-explanatory, designed for quick decision-making.
🔍 Unlock Hidden Insights: Beyond the provided metrics, explore new insights that could help understand and solve the decline in active users and revenue.

📊 Dataset Provided
The dataset includes various tables capturing data related to cities, dates, plans, revenue, active users, and market share, providing the foundational data required for in-depth analysis and comparison before and after the 5G rollout.

dim_cities: city_code, city_name
dim_date: date, month_name, before/after_5g, time_period
dim_plan: plan, plan_description
fact_atliqo_metrics: date, city_code, company, atliqo_revenue_crores, arpu, active_users_lakhs, unsubscribed_users_lakhs
fact_market_share: date, city_code, tmv_city_crores, company, ms_pct
fact_plan_revenue: date, city_code, plans, plan_revenue_crores

🛠️ Tools Used

Power BI 🖥️
Data Transformation 🔧
KPI Cards 🏆
Interactive Charts 📊
Bookmarks & Slicers 🔖🎛️
Custom Measures 📏

📈 Key Measures

Total Revenue 💰
Average Revenue (ARPU) 📉
Total Active Users 👥
Total Unsubscribed Users 🚫
Market Share % 📊
Revenue Before & After 5G 🔄
ARPU Before & After 5G 🔄
Active Users Before & After 5G 🔄

💡 Key Insights

🔻 Revenue Decline Post-5G: A noticeable loss in average revenue after 5G. Pricing strategies may need review. 💸
📉 Drop in Active Users: Monthly active users have decreased post-5G, indicating a need for re-engagement campaigns. 📅
💔 Lost Revenue: A significant revenue drop after 5G suggests users aren’t finding enough value in new plans.
💰 Total Plan Revenue: ₹1.95K total plan revenue. Potential for growth if customer preferences align better with the offerings.
🏆 Market Share Leaders: PIO leads, followed by Britel, AtliQo, Dadafone, and others. AtliQo’s growth potential lies in closing the gap.
📍 Delhi Dominates: Delhi holds 26.36% of market value—strategies for other cities could help balance the playing field.
📊 Lucknow & Gurgaon: These cities show a significant revenue increase post-5G, indicating a successful strategy in these regions.
🚫 Ahmedabad, Delhi, & Raipur: Declining monthly active users in these cities, suggesting a need for localized improvements.
🚷 High Unsubscribed Users: Mumbai, Delhi, and Kolkata report the highest unsubscribed user rates—identify root causes for churn.
💸 Mumbai & Delhi Lead in Plan Revenue: Mumbai and Delhi generate the highest revenue, indicating prime areas for future growth.


🔧 Actionable Recommendations

💡 Re-assess Pricing Models: Introduce flexible pricing or value-added services to boost user retention and attract new users.
🔍 User Re-engagement: Focus on cities with declining users (Ahmedabad, Delhi, Raipur) through targeted marketing and offers.
📊 Market Expansion: Investigate strategies to increase AtliQo’s market share in underperforming regions.
💬 Unsubscribe Feedback: Engage unsubscribed users to identify pain points and address them with new plan offerings.
