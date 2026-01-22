# Hotel Booking Cancellation Prediction & Revenue Optimization

A machine learning project developed to predict booking cancellations for a hotel chain, enabling data-driven strategies to protect revenue. This project analyzes booking patterns, identifies key cancellation drivers, and builds high-accuracy predictive models.

## Business Problem
The INN Hotels Group faced significant revenue risk due to a high volume of booking cancellations. This project delivers a predictive system to identify at-risk bookings in advance, allowing for proactive interventions like targeted guest communication and optimized overbooking policies.

## Dataset & Initial Insights
* **Records:** 36,275 bookings
* **Cancellation Rate:** 33%
* **Key Segments:** Online Travel Agents (OTA) dominated the market (60% of bookings).
* **Primary Drivers:** Initial exploratory data analysis (EDA) revealed **lead time** and **average daily rate (price)** as the strongest factors influencing cancellation likelihood.

## Methodology & Technical Approach
1. **Exploratory Data Analysis (EDA):** Performed comprehensive analysis using box plots and histograms to understand data distributions, outliers, and correlations.
2. **Data Preprocessing:** Handled missing values, encoded categorical variables, and scaled features.
3. **Dimensionality Reduction:** Applied **Principal Component Analysis (PCA)**, reducing 18 original features to 5 principal components that explain **58.3% of the variance**, effectively mitigating multicollinearity.
4. **Model Development & Evaluation:** Built, trained, and compared multiple classification models:
   * **Logistic Regression:** Achieved ~99% accuracy after addressing multicollinearity.
   * **Decision Tree Classifier:** Achieved ~100% accuracy with excellent generalization.
   * **Validation:** All models demonstrated robust performance with ROC-AUC scores of **0.999+**, indicating exceptional classification capability.

## Key Results & Business Impact
The predictive system provides management with actionable insights for:
* **Early Warning:** Identify bookings with high cancellation probability.
* **Revenue Protection:** Target retention efforts on the riskiest 20% of bookings.
* **Operational Efficiency:** Optimize staff scheduling and inventory allocation based on predicted cancellation patterns.
* **Strategic Policies:** Formulate profitable cancellation and refund policies.

## Actionable Recommendations
Based on model insights, recommended business strategies include:
* Implementing **tiered deposit schemes** for high-risk bookings.
* Offering **non-refundable discount rates**.
* Applying **predictive overbooking** (8-12%) during high-cancellation months.
* Adjusting **dynamic pricing** strategies for cancellation-prone segments.
