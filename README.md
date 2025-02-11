# Build Propensity to Purchase Model in Python

## Business Objective
Our client is an early-stage e-commerce company selling various products from daily essentials (such as dairy & vegetables) to high-end electronics and home appliances. It is a one-year-old company experiencing many visitors searching for products, but only a few complete a purchase.

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

## Modular Code Overview
The project is organized into the following folders:

### 1) `input` Folder
Contains all the necessary data for analysis:
- **Config file**: Basic configuration parameters (editable as per dataset).
- **final_customer_data.xlsx**: 2090 rows of customer transaction data with nine features.
- **final_customer_data_with_RFM_features.csv**: Merged dataset containing customer data and extracted RFM values.
- **ecom_product_data.csv**: Transaction dataset from 01/12/2010 to 09/12/2011 for a UK-based online retail store, used to demonstrate RFM modeling.

### 2) `src` Folder
Contains the modularized code:
- **engine.py**: Main script that calls functions.
- **ml_pipeline/**: Folder containing different functions in Python files for modular processing.
- **requirements.txt**: Install dependencies using:
  ```bash
  pip install -r requirements.txt
  ```

### 3) `output` Folder
Stores the trained model, which can be used for future predictions without retraining from scratch.

### 4) `lib` Folder
Reference folder containing original Jupyter notebooks.

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

## 📌 Getting Started
To run this project locally:
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
   
