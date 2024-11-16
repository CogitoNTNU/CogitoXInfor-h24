# Cogito x Infor Project

## Overview
This project is a collaboration between **Cogito**, a student organization, and **Infor**, the third-largest company globally for enterprise systems. The goal was to develop a dynamic pricing model using data science techniques and to integrate insights into EA Smith's pricing strategy for improved profitability.

---
# Quickstart Guide for Jupyter Notebooks

This guide provides an overview of the uploaded Jupyter notebooks and how to get started with them.

---

## Available Notebooks

### 1. `FastMarketsAPI/APICall.ipynb`
- **Purpose**: Demonstrates how to interact with an API to fetch data.
- **Features**:
  - API key authentication.
  - Sending requests and parsing JSON responses.
  - Error handling for failed API calls.

#### Quickstart
**Contact EA. Smith, FastMarkets or Thomas for API KEY**
1. Ensure Python and required libraries are installed:
   ```bash
   pip install requests
### 2. `PriceRecommender/FinalNotebookCogito.ipynb`
The `FinalNotebookCogito.ipynb` notebook is a key component of the **Price Recommender Project**. It focuses on creating a dynamic pricing recommendation model through advanced data processing, clustering, and evaluation techniques.

---

### Key Features

#### 1. **Data Preprocessing**
   - **Input Dataset**:
     - Source: `ECOMMRecords 2020` (or similar structured data).
     - Content: Product and customer information for pricing insights.
   - **Cleaning Steps**:
     - Handle missing data.
     - Normalize numerical features.
     - Encode categorical variables.

#### 2. **Feature Engineering**
   - Extracted key features from the dataset for clustering.
   - Feature selection includes:
     - Product category.
     - Customer segment.
     - Historical purchase behavior.

#### 3. **Clustering Analysis**
   - **K-Means Clustering**:
     - Group products and customers into clusters based on similarities.
   - **Evaluation**:
     - Silhouette score to determine the optimal number of clusters.
     - Cluster visualization to ensure meaningful segmentation.

#### 4. **Price Recommendation Model**
   - Uses the clusters to recommend optimal prices.
   - Customizes margins for each product-customer combination.

#### 5. **Visualizations**
   - Graphical representations of clusters.
   - Distribution plots for customer and product clusters.
   - Insights into recommended pricing adjustments.

---

## How to Use

### Prerequisites
- **Dependencies**:
  Install the required Python libraries using:
  ```bash
  pip install pandas numpy scikit-learn matplotlib seaborn
## Team

- **Project lead**: Thomas   
- **Members/Developers**: Herman, Baris, Nikolai, Gard  


---

## Problem
EA Smith faced challenges with:
- **Unclear pricing strategies**
- **Limited market insights**

This resulted in **poor pricing decisions** and **reduced profit margins**.

---

## Solution
The team developed a pricing recommendation model using **unsupervised learning** to identify natural clusters in product and customer data. Key benefits of this approach include:
- No need for historical data
- Tailored margin recommendations for product-customer combinations
- High interpretability

---

## Methodology

### Data Collection
- Dataset: **ECOMM Records 2020** from Kaggle
- **Additional scraping** via APIs to gather competitor pricing.

### Modeling Approach
1. **Feature Engineering**:
   - Customer and product attributes were processed for clustering.
2. **K-Means Clustering**:
   - Analyzed clusters and optimized the model using silhouette scores.
3. **Pricing Recommendations**:
   - Margins were adjusted dynamically per cluster.

### Competitor Analysis
- Developed an **API scraper** to:
  - Compare EA Smith's prices with competitors.

### Currency Conversion
- Integrated an API to convert prices from EUR to NOK for localized analysis.

---

## Key Features
- **Dynamic Pricing Model**:
  - Custom margin recommendations using unsupervised learning.
- **API Integration**:
  - Fetch competitor prices dynamically.

---

## Results
- **Improved Pricing Strategies**:
  - Tailored price recommendations by cluster.
- **Market Insights**:
  - Clear competitor comparison through API scraping.

---

## Future Plans
- Continued collaboration with Infor for extended features.
- Enhanced dynamic pricing models for broader adoption.

---

## Acknowledgments
In collaboration with Infor and EA. Smith

---