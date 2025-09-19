# Airline-Satisfaction-Analysis

## Project Overview
This project analyzes factors influencing airline passenger satisfaction using a dataset of 120,000+ passenger surveys. The goal is to identify key drivers of satisfaction and provide actionable business recommendations.

---

## Business Problem
Airlines need to understand what drives passenger satisfaction to improve service quality, increase customer loyalty, and reduce churn in a highly competitive market.

## Dataset
Source: [Kaggle - Airline Passenger Satisfaction](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction)
Liscense: Please refer to the original source for dataset licensing information.

The dataset contains passenger survey responses including:
- Demographic information (Age, Gender, Customer Type)
- Travel details (Class, Type of Travel, Flight Distance)
- Service ratings (13 different service aspects rated 1-5)
- Flight operations (Departure/Arrival Delays)
- Overall satisfaction (Satisfied/Neutral or dissatisfied)

## 📊 Key Findings

### 1. Service Quality Drivers
- **Online boarding experience** is the strongest predictor of satisfaction (correlation: 0.59)
- **Inflight entertainment** and **seat comfort** are the next most important factors
- **Baggage handling** has the weakest correlation with overall satisfaction

### 2. Customer Segmentation Insights
- **Loyal business travelers** have the highest satisfaction rate (87.3%)
- **Disloyal personal travelers** have the lowest satisfaction rate (38.1%)
- **Business class passengers** are 2.4x more likely to be satisfied than Eco class passengers

### 3. Operational Impact
- **Departure delays** strongly correlate with arrival delays (r = 0.96)
- **Long delays** (>60 minutes) reduce satisfaction by 22% compared to on-time flights
- **Age** shows a weak but positive correlation with satisfaction (r = 0.11)

## Predictive Modeling Results
- **Random Forest Classifier** achieved 96.2% accuracy in predicting satisfaction
- **Logistic Regression** achieved 86.7% accuracy
- Top 5 predictive features:
  1. Online boarding
  2. Inflight entertainment
  3. Seat comfort
  4. Type of Travel (Business)
  5. Class (Business)

  --- 

## Technologies Used
- **Python 3.8+**
- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Machine Learning**: Scikit-learn
- **Statistical Analysis**: SciPy
- **Environment**: Google Colab

## How to Run This Project

### Google Colab
1. Open Google Colab (colab.research.google.com)
2. Upload the three notebooks from the `notebooks/` folder
3. Run each notebook sequentially (01 → 02 → 03)
4. Download the dataset from Kaggle and upload to Colab when prompted

---

## 🎯 Business Recommendations

### Immediate Actions (0-3 months)
1. Improve online boarding process - streamline digital check-in and mobile boarding passes
2. Enhance inflight entertainment - upgrade content library and system reliability
3. Target business travelers - develop loyalty programs specifically for this high-value segment

### Medium-Term Initiatives (3-12 months)
1. Implement predictive analytics - use the model to identify at-risk passengers pre-flight
2. Create segment-specific services - differentiate offerings for business vs. personal travelers
3. Invest in seat comfort - prioritize cabin upgrades based on customer feedback

### Long-Term Strategy (12+ months)
1. Develop real-time monitoring - create dashboards to track satisfaction metrics
2. Establish service recovery protocols - proactive intervention for delayed flights
3. Continuous feedback integration - regular passenger surveys and feedback implementation

## Future Enhancements
- Implement deep learning models for improved accuracy
- Create interactive dashboard for airline management
- Add time series analysis to track satisfaction trends
- Incorporate external data (weather, economic factors)

---

The code and analysis in this repository are licensed under the MIT License - see the LICENSE file for details.
