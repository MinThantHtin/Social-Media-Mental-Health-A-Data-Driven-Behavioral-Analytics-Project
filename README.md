# 📊 Social Media vs Mental Health: Data-Driven Behavioral Analysis

## 🧩 Overview
This project analyzes the relationship between social media usage and mental health using a real-world dataset. The goal is to uncover behavioral patterns and provide data-driven recommendations to improve well-being.

---

## 💼 Business Problem
With increasing social media usage, understanding its impact on mental health is critical for platforms, healthcare providers, and digital product companies.

This project answers:
- How does social media usage affect mental health?
- What is the optimal usage level?
- Which users are at high risk?

---

## 📂 Dataset
- Source: Kaggle (Mental Health & Social Media Balance Dataset)
- Features include:
  - Daily usage hours
  - Sleep hours
  - Stress levels
  - Mental health scores

---

## 🧠 Feature Engineering
- Created usage categories (Low, Moderate, High)
- Identified sleep deprivation
- Built a custom "well-being score"

---

## 📊 Key Insights
- High social media usage (>5 hours) is associated with lower mental health scores
- Moderate usage (2–4 hours) shows the best well-being outcomes
- Sleep deprivation significantly reduces mental health
- High-risk users: high usage + low sleep

---

## 🚨 Risk Detection
Users with:
- High usage (>5 hours)
- Low sleep (<6 hours)

→ Show significantly lower mental health scores

---

## 📈 Dashboard
The Tableau dashboard provides:
- Behavior analysis (usage vs mental health)
- Sleep impact visualization
- Risk segmentation

![Dashboard](dashboard/dashboard_screenshots.png)

---

## 💡 Business Recommendations
- Encourage users to limit usage to 2–4 hours/day
- Promote healthy sleep habits through app features
- Implement alerts for high-risk users

---

## 🚀 Product Idea
A smart mental health assistant that:
- Monitors user behavior
- Detects high-risk patterns
- Provides personalized recommendations

---

## 🛠️ Tech Stack
- Python (Pandas, Matplotlib, Seaborn)
- Tableau
- Jupyter Notebook

---

## 📌 Future Improvements
- Add machine learning prediction model
- Deploy as a web application
- Real-time monitoring system
