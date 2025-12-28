# Hotel Booking Cancellation Analysis

## Business Problem
Hotel cancellations create revenue loss and make demand forecasting difficult.  
This project analyzes hotel booking data and customer reviews to **predict cancellations** and generate actionable recommendations for hotel management. The goal is to improve **occupancy, pricing strategies, and customer retention**.

---

## Dataset
- Public hotel booking dataset (~15,000 rows, 20 variables)  
- Includes numerical and categorical features describing bookings, customers, and stays  
- Target variable: **cancellation** (0 = not cancelled, 1 = cancelled)  
- Data not included due to size and privacy considerations  

### Key Variables
| Variable | Description |
|----------|-------------|
| `days_before_arrival` | Lead time in days between booking and arrival |
| `deposit_type` | No deposit / Refundable / Non-refundable |
| `market_segment` | Direct, Online TA, Groups, etc. |
| `special_requests` | Number of special requests made by the customer |
| `target` | Cancellation indicator (1 = cancelled) |

---

## Methods & Analysis
- Followed **CRISP-DM framework** 
- **Machine Learning Models:** Logistic Regression, Decision Trees, Random Forest, Neural Networks  
- **Other Analyses:** Market Basket Analysis, Sentiment Analysis, Topic Modeling  
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1 Score, ROC-AUC, MSE, Gini Coefficient  

---

## Key Insights
- Long lead times and refundable/non-deposit bookings increase cancellation risk  
- Online travel agencies show higher cancellation rates  
- Customer engagement (special requests, repeat guests) reduces cancellation probability  
- Reviews emphasize cleanliness, staff behavior, and breakfast quality  

---

## Business Recommendations
- Apply stricter refund policies for high-risk bookings  
- Encourage customer engagement and loyalty programs  
- Use predictive flags to proactively manage risky bookings  
- Monitor feedback to improve services that matter most to customers

---

## Tools & Technologies
- Python (pandas, scikit-learn, NLP libraries)  
- Machine Learning & Statistical Modeling  
- Data Visualization (matplotlib, seaborn, plotly)  
- Business Analytics & Decision Support  

---

## Notes
- All steps are **fully reproducible** using the provided notebook  
- This project demonstrates both **technical skills** and **business-driven insights**

