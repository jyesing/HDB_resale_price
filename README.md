# HDB Resale Price Analysis 🏡

## 📌 Overview
This project analyzes HDB resale transactions in Singapore from 2017 to present, identifying key price drivers and building a predictive pricing model.

## 🎯 Objectives
- Analyze price trends over time
- Identify key factors affecting resale prices
- Detect undervalued transactions
- Build a model to estimate fair property value

## 🔍 Key Insights
- Location and remaining lease are the strongest drivers of price
- Floor area significantly impacts resale value
- Storey level has relatively weak influence
- Prices surged significantly after 2020

## 🤖 Model
- Linear Regression model used
- Predicts resale price based on:
  - Town
  - Flat type
  - Floor area
  - Remaining lease
  - Storey category

## ⚠️ Limitations
- Model does not include:
  - MRT distance
  - Exact block location
  - Renovation condition

## 📊 Tools Used
- Python
- Pandas
- Matplotlib
- Scikit-learn

## 📁 Files
- `2nd_Project_HDB_resale_since_2017.ipynb` → Main analysis notebook
