# eBay Laptop Price Prediction

## Overview
A machine learning project that predicts laptop resale prices using eBay sales data. This project demonstrates end-to-end ML pipeline development with real-world, messy data - directly applicable to reverse logistics and recommerce applications.

**Business Context**: In reverse logistics, accurately predicting resale value is critical for optimal disposition decisions (resell, refurbish, liquidate, or recycle).

## Project Status
🚧 **In Progress** - Currently implementing data cleaning and feature engineering

## Dataset
- **Source**: Kaggle eBay laptop sales data
- **Size**: 6,620 records with 23 features
- **Key Challenges**: Missing brand data (39%), inconsistent price formats, varied condition descriptions

## Technical Roadmap

### ✅ Phase 1: Data Exploration & Clean Up
- [x] Initial data exploration and quality assessment
- [x] Price field cleaning (handles ranges and single prices)
- [ ] Brand analysis and cleanup strategy development
- [ ] Brand cleanup implementation
- [ ] Condition cleanup

### 🚧 Phase 2: Feature Engineering (In Progress)
- [ ] Brand standardization and unknown category creation
- [ ] Condition field normalization (ordinal encoding)
- [ ] Processor tier extraction (i7 > i5 > Celeron)
- [ ] Storage capacity normalization
- [ ] Screen size standardization

### ⏳ Phase 3: Model Development
- [ ] Baseline Linear Regression model
- [ ] Multi-Layer Perceptron (MLP) neural network
- [ ] Model comparison and evaluation
- [ ] Hyperparameter tuning

### ⏳ Phase 4: Model Evaluation & Insights
- [ ] Performance metrics analysis
- [ ] Feature importance analysis
- [ ] Business insights and recommendations
- [ ] Model deployment considerations

## Key Features
- **Price Cleaning**: Handles both single prices and ranges (uses average for ranges)
- **Brand Standardization**: Maps 134+ brand variations to standardized categories
- **Condition Normalization**: Creates ordinal hierarchy for refurbishment levels
- **Production-Ready Code**: Modular functions, proper error handling, documentation

## Technologies
- **Data Processing**: Pandas, NumPy
- **Machine Learning**: Scikit-learn, TensorFlow/Keras
- **Environment**: Google Colab, Python 3.x

## Business Applications
This price prediction model directly supports:
- **Automated disposition decisions** in reverse logistics
- **Dynamic pricing strategies** for recommerce platforms
- **Inventory valuation** for returned electronics
- **ROI optimization** in refurbishment operations

## Project Files
- `eBay_Price_Prediction.ipynb` - Main analysis notebook
- `README.md` - Project documentation

---
*This project demonstrates practical ML engineering skills for real-world e-commerce and reverse logistics applications.*
