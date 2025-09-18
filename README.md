# Customer Segmentation Analysis

## Overview

This project presents an in-depth analysis of customer data to uncover meaningful segments based on demographic characteristics and spending behavior. By clustering similar customers, businesses can gain actionable insights to enhance audience understanding and develop targeted marketing strategies that maximize engagement and profitability.

The analysis primarily employs clustering techniques, with a focus on K-Means clustering, supported by comprehensive data exploration and visualization.

---

## Dataset

The analysis utilizes the `Mall_Customers.csv` dataset, comprising information on 200 customers with the following features:

- **CustomerID**: Unique identifier for each customer
- **Gender**: Male or Female
- **Age**: Age of the customer
- **Annual Income (k$)**: Annual income in thousands of dollars
- **Spending Score (1–100)**: Score assigned by the mall based on customer spending patterns

---

## Analytical Workflow

### 1. Data Preparation
- Assessed and addressed missing values in the dataset
- Converted categorical variables (e.g., Gender) into numerical representations
- Selected relevant features for effective clustering

### 2. Exploratory Data Analysis (EDA)
- Examined distributions of Age, Annual Income, and Spending Score
- Analyzed the gender composition of the customer base
- Explored relationships between Annual Income and Spending Score

### 3. Clustering Process
- Utilized the Elbow Method to identify the optimal number of clusters
- Implemented K-Means clustering on selected features
- Visualized the resulting clusters using both 2D and 3D scatter plots for interpretability

---

## Key Insights

The clustering analysis revealed distinct customer segments, including but not limited to:

- **High Income, High Spenders**: Premium target customers for exclusive offerings
- **High Income, Low Spenders**: Potential segment for promotional campaigns to increase engagement
- **Average Income, Moderate Spenders**: Stable group valuable for consistent revenue streams
- **Low Income, High Spenders**: Opportunity for tailored loyalty or discount programs

---

## Results

The segmentation process uncovered clear behavioral patterns:

- Customers with both high income and high spending scores are ideal candidates for premium services and loyalty initiatives.
- High-income customers with low spending represent an untapped opportunity for targeted marketing efforts.
- Segments with average or lower income can be engaged and retained through value-driven programs, such as discounts or rewards.

---

## Running the Analysis

### Prerequisites

Install the required Python libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### Steps

1. Launch the Jupyter Notebook:

    ```bash
    jupyter notebook "Customer Segmentation Analysis.ipynb"
    ```

2. Execute the cells sequentially to follow the analysis, visualizations, and insights.

---

## Potential Extensions

- Compare segmentation outcomes with alternative methods such as Hierarchical Clustering.
- Develop an interactive dashboard using Streamlit or Dash for real-time segment exploration.
- Incorporate advanced feature engineering to further refine segment definitions and business recommendations.

---

## Contact

For further information or collaboration opportunities, please contact the project maintainer.
