### Comprehensive Document for Amazon Demand Forecasting Data Scientist Role Application

#### 1. **Project 1: Amazon Sales Data Analysis**
   - **Objective**: Analyze product attributes like price, reviews, and star ratings to uncover factors impacting product popularity and pricing. Apply clustering and regression techniques to predict price and popularity scores.
   - **Data Source**: https://www.kaggle.com/datasets/asaniczka/amazon-products-dataset-2023-1-4m-products
   - **Steps Taken**:
     1. **Data Cleaning and Preparation**: Combined Amazon products and categories datasets, managed missing values, and calculated derived features like `discount_percentage`.
     2. **Feature Engineering**: Added features such as `popularity_score` (a combination of stars and reviews), `category frequency`, and `price range`, with category frequency indicating how popular certain categories were across the dataset.
     3. **Clustering**: Applied K-Means to segment products based on characteristics like price and popularity, which helped distinguish patterns among different product groups.
     4. **Regression Models**:
         - Implemented models like **Linear Regression, Random Forest, Ridge Regression, Lasso Regression, and XGBoost** to predict product pricing.
         - Random Forest and XGBoost stood out with the lowest Mean Squared Errors and higher R² scores, confirming their robustness in capturing complex relationships.
     5. **Model Interpretability**: Employed SHAP to interpret Random Forest feature importance, confirming the influence of factors like `category frequency` and `price range`.

   - **Results**:
     - **Key Insights**:
       - Products with higher discount percentages and popularity scores typically see better engagement.
       - Random Forest and XGBoost proved effective, especially in handling non-linearities within the data.
     - **Impact**: These insights into factors affecting Amazon product popularity illustrate my grasp of feature engineering, clustering, and regression modeling, aligning with Amazon's customer-driven focus in demand forecasting.

#### 2. **Project 2: Walmart Sales Data Forecasting**
   - **Objective**: Forecast weekly sales using Walmart’s cleaned sales data, exploring both traditional time series models and advanced regression approaches.
   - **Data Source**: https://www.kaggle.com/datasets/ujjwalchowdhury/walmartcleaned
   - **Steps Taken**:
     1. **Exploratory Data Analysis**: Assessed trends in sales, seasonal patterns, and correlations, particularly noting the positive impact of store size on weekly sales.
     2. **Outlier Analysis**: Employed Z-scores to identify outliers, which were addressed to enhance model reliability.
     3. **Time Series Modeling**:
         - Implemented **ARIMA, SARIMA, and Exponential Smoothing**, capturing trends and seasonality in the dataset.
         - **SARIMA** and **ARIMA** demonstrated strong performance in trend forecasting, while **Exponential Smoothing** provided smooth forecasts suited for steady demand periods.
     4. **Machine Learning Models**:
         - **Random Forest and Quantile Regression Forest (QRF)** were applied for their robustness in handling high-dimensional data, offering probabilistic forecasting.
         - **Explored Temporal Fusion Transformer (TFT)** as a potential next step, reflecting my understanding of Amazon’s interest in advanced models for time series forecasting. Although not fully developed in this project, I’m eager to deepen my understanding of transformer-based models.

   - **Results**:
     - **Key Findings**:
       - Time series models like ARIMA and SARIMA effectively captured seasonality and general trends, proving reliable for steady, predictable sales.
       - QRF provided probabilistic insights, aligning with Amazon's approach of using quantile forecasts to manage demand uncertainty.
     - **Impact**: This project exemplifies the variety of forecasting methods Amazon employs, showcasing my ability to apply both traditional and advanced forecasting models, contributing toward accurate demand forecasting.

#### 3. **Project 3: Progress Note Understanding for Assessment and Plan Reasoning - Attached Report **

#### **Conclusion and Fit for Amazon Demand Forecasting Role**
Through these projects, I’ve illustrated my skills across:
1. **Data Preparation and Feature Engineering**: I employed data transformation techniques and created meaningful features that offered actionable insights into product and sales data.
2. **Demand Forecasting**: By exploring SARIMA, ARIMA, and advanced approaches like Random Forest and Quantile Regression Forest, I demonstrated an understanding of Amazon’s time series forecasting evolution, reflecting my commitment to adapting these techniques for real-world applications.
3. **Advanced Modeling and Experimentation**: My exploration of SHAP and transformer-based forecasting models aligns with Amazon’s focus on transparency, adaptability, and innovation in probabilistic forecasting.

**Why I am a Strong Candidate**: My progression from traditional time series models to exploratory work with transformers positions me to meaningfully contribute to Amazon’s forecasting team. I am eager to further deepen my expertise, including working with transformer-based models like MQTransformer, aligning with Amazon's pioneering advancements in demand forecasting.
