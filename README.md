# Build Propensity to Purchase Model in Python

## Business Objective
The business case: our client is an early-stage e-commerce company selling various products from daily essentials (such as dairy & vegetables) to high-end electronics and home appliances. It is a one-year-old company experiencing many visitors searching for products, but only a few complete a purchase.

To increase the number of purchases, the business plans to send discounts or coupons to motivate users to buy. However, since it is an early-stage startup, funds for this campaign are limited. Thus, they seek our help in building a model that predicts the purchase probability of each user.

We will use **propensity modeling**, which forecasts user behavior based on past actions. This model will help identify users most likely to purchase, allowing targeted marketing strategies that improve ROI while minimizing unnecessary discount distribution.

Additionally, we will utilize **RFM Modeling** (Recency, Frequency, and Monetary value) to segment users based on key purchasing traits. This will allow for better user engagement, retention, and personalized marketing strategies.

## Data Description
The dataset contains the purchase history of various users over a period of time for an e-commerce company.

## Aim
1. Understand **Propensity Modeling**.
2. Understand **RFM Analysis**.
3. Build a model to predict the **purchase probability** of each user.

## Tech Stack
- **Language**: Python
- **Libraries**: pandas, sklearn, numpy, seaborn, datetime, matplotlib, missingno

## Approach
1. Import required libraries and packages.
2. Read the dataset (CSV file).
3. Perform **data preprocessing**.
4. Conduct **exploratory data analysis**:
   - Univariate analysis
   - Multivariate analysis
5. Perform **RFM Analysis**.
6. Conduct **feature engineering**.
7. Create **modeling data**.
8. Build the model.
9. Make predictions.


## Project Takeaways
1. Understanding **propensity modeling**.
2. Performing **univariate and multivariate analysis**.
3. Data **preprocessing** techniques.
4. Understanding **RFM modeling** and how to calculate RFM features.
5. How to **encode categorical variables**, scale data, and perform data transformation.
6. Building a **logistic regression model**.
7. Using RFM features to identify **purchase propensity**.
8. Implementing **preferential treatments and high-value paths**.
9. Visualizing data with **matplotlib** and **seaborn**.

---

### 🚀 Future Enhancements
- Experiment with other **machine learning models** (e.g., Random Forest, XGBoost).
- Optimize feature selection and hyperparameter tuning.
- Develop an **API endpoint** for real-time predictions.

---

## To run this project locally:
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd propensity-model
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the main script:
   ```bash
   python src/engine.py
   
