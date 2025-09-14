# mall-customer-segmentation
# Project Overview

This project applies K-Means clustering to segment mall customers based on Annual Income and Spending Score. The goal is to uncover distinct customer groups that can support targeted marketing strategies, personalized offers, and customer relationship management.

# Tools & Libraries

- Python

- Pandas → data preprocessing & transformation

- Seaborn, Matplotlib → exploratory data analysis & visualization

- Scikit-learn → K-Means clustering, StandardScaler

# Project Workflow

- Data Loading & Cleaning

Imported dataset with Pandas

Checked data types, distributions, and missing values

- Exploratory Data Analysis (EDA)

Visualized distributions of income, spending, and age

Analyzed correlations between features

- Feature Scaling

Applied StandardScaler to normalize numerical features

- K-Means Clustering

Ran clustering on multiple feature combinations (Income, Spending Score, Age)

Used Elbow Method to determine optimal cluster count

- Visualization & Insights

Scatterplots of clusters (e.g., Income vs Spending Score)

Cluster centers visualized for interpretation

Elbow curve plotted for cluster evaluation

# Results & Insights

- Optimal clusters identified = 5

- Distinct customer segments observed:

   - High Income – High Spending (Potential Premium Customers)

   - High Income – Low Spending (Untapped Segment)

   - Moderate Income – Moderate Spending

   - Low Income – High Spending (Value Seekers)

   - Low Income – Low Spending (Budget Customers)

- Insights support segmentation-driven decision-making in retail strategy.

# Key Skills Demonstrated

- Data preprocessing & cleaning

- Exploratory data analysis (EDA)

- K-Means clustering & evaluation (Elbow Method)

Customer segmentation analysis

Data visualization for business insights
