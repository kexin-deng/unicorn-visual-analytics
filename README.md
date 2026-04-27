# 🦄 Fantastic Unicorns and Where to Find Them

**Authors:** Linjing Cai, Kexin Deng  
**Date:** May 2024  

---

## 📌 Overview

This project explores the global landscape of unicorn companies (privately held startups valued at over $1B) through interactive data visualization. The goal is to uncover patterns in geographic distribution, industry concentration, and temporal dynamics, enabling a deeper understanding of what drives unicorn success.

We design a web-based visualization system to help users explore:

- Where unicorns are located globally  
- Which industries dominate the unicorn ecosystem  
- How unicorn emergence evolves over time  

---

## 🎯 Objectives

- Analyze global trends in unicorn company formation  
- Visualize relationships between industry, geography, and valuation  
- Identify patterns across economic cycles (e.g., Financial Crisis, COVID-19)  
- Provide an intuitive and interactive exploration experience  

---

## 📊 Dataset

The dataset is sourced from Kaggle and contains over **1,200 unicorn companies** worldwide.

**Key features include:**
- Company name  
- Valuation (in billions USD)  
- Date joined (unicorn status)  
- Country and city  
- Industry  

This structured dataset enables both categorical and quantitative analysis. :contentReference[oaicite:0]{index=0}

---

## 🧠 System Design

The visualization is organized into three main views:

### 🌍 1. Country View
- Interactive world map showing distribution of unicorn companies  
- Hover to view country-level statistics  
- Click to reveal:
  - Top companies (bar chart)  
  - Industry breakdown (pie chart)  

### 🏭 2. Industry View
- Treemap visualization of unicorn companies by sector  
- Enables comparison of valuations across industries  
- Supports drill-down exploration  

### ⏳ 3. Time Horizon View
- Time series analysis of:
  - Number of unicorns per year  
  - Global GDP trends  
  - Industry proportions  
- Highlights major global events (e.g., 2008 Financial Crisis, COVID-19)  

---

## ✨ Key Insights

- Unicorn growth is highly concentrated in technology-driven industries  
- Geographic clustering is prominent in the US and China  
- Economic shocks (e.g., COVID-19) significantly impact unicorn formation trends  
- Certain sectors (e.g., healthcare) surge during crisis periods  

---

## 🛠️ Technologies Used

- JavaScript (D3.js for visualization)  
- HTML / CSS  
- Data preprocessing (Python / manual cleaning)  

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/your-repo-name.git
