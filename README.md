# 🛍️ K-Means – Mall Customer Segmentation

This project applies **K-Means clustering** to the Mall Customer dataset to group shoppers based on demographic and spending behavior. By clustering customers using features like annual income and spending score, the model uncovers distinct customer groups that enable targeted marketing, personalized services, and smarter business strategies.

---

## 🎯 Project Objective
Use unsupervised learning to:
- Discover hidden customer segments
- Analyze purchasing behaviors and spending patterns
- Support business decisions and customer retention
- Improve marketing personalization and resource allocation

---

## 👥 Dataset Overview
Typical dataset fields:
- **Age**
- **Gender** (if encoded)
- **Annual Income**
- **Spending Score**

> Replace or update based on the dataset you used.

---

## 🧠 Why K-Means?
K-Means clustering:
- Groups customers by similarity
- Helps reveal shopping personas
- Is fast, scalable, and easy to interpret
- Works well with numerical marketing data

Requires selecting a cluster count `k` — example: `k = 3`.

---

## 🧪 Implementation Steps
1. Load and inspect dataset  
2. Clean data and encode/scale features  
3. Create a KMeans model  
4. Fit on scaled data and assign cluster labels  
5. Explore and visualize results

# Visualization & Insights

Visualizations help interpret cluster meaning.

## Plots Included
- Income vs Spending Score scatterplots
- Cluster-colored grouping
- Optional PCA to plot in 2D

## Common Cluster Patterns
- High-income, high-spend luxury customers
- Mid-income, moderate spenders
- Budget-conscious shoppers

---

## Business Use Cases

K-Means segmentation helps businesses:
- Target campaigns by shopper type
- Avoid over-discounting premium customers
- Build loyalty strategies
- Design personalized experiences
- Make store layout/product plans based on data
- Boost ROI with smarter targeting

---

## Tools Used
- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib / Seaborn

---

## Key Outputs
- Cluster-labeled customer dataset
- Segmentation insights for marketing teams
- Plots showing customer group separation
- New shopper personas for business analysis
- Reusable machine learning workflow

---

## Future Enhancements

To make the model more powerful, we plan to:
- Test different values of K using silhouette score
- Compare with other clustering techniques:
  - Hierarchical Clustering
  - DBSCAN
  - Gaussian Mixture Models
- Add more business features:
  - Online purchase behavior
  - Loyalty tier
  - Recency–Frequency–Monetary (RFM) metrics
- Create an interactive Streamlit dashboard
- Automate segmentation updates over time
- Deploy using Flask/FastAPI
- Package with Docker for flexible environments

---

## Notebook File
`kmeans-mall-customer-segmentation.ipynb`

---

## Conclusion
K-Means clustering uncovers meaningful customer groups hidden in mall shopping data. By analyzing income and spending score patterns, businesses can identify high-value customers, budget-conscious buyers, and mid-range shoppers. This enables smarter decision-making, improved customer experience, and increased profitability.

Unsupervised learning transforms simple customer records into valuable, actionable intelligence.

