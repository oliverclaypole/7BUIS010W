7BUIS010W.2 Data Warehousing and Business Intelligence Coursework

Project Overview:
This project leverages Python-based data analytics and machine learning to segment S&P 500 stocks based on their risk-return profiles. By calculating Beta, Annual Volatility, and Mean Daily Returns, we categorize 496 stocks into three distinct investment regimes (Defensive, Moderate, and Aggressive).
The goal is to provide a Business Intelligence framework that supports automated investment advice and ESG-aligned portfolio management within a Fintech context.

You can view the full analytical report here: [Final_Report.pdf](Final_Report.pdf)
You can view the full code here: [SP5000_Risk_Clusterring_Analysis.ipynb](SP5000_Risk_Clusterring_Analysis.ipynb)

This project requires Python 3.x and the following libraries:

Data: `yfinance`, `pandas`, `numpy`
Visualisation: `matplotlib`, `seaborn`
Machine Learning: `scikit-learn`

To install all dependencies at once, run:
```bash
pip install yfinance pandas numpy matplotlib seaborn scikit-learn
```
<details>
  <summary><b>Click to view Technical Visualisations</b></summary>
  
  <br>

  ### Agglomerative Clustering
  Visualising the spatial separation of equities based on Return, Beta, and Volatility.
  ![3D Cluster Map](Agglomerative_Clustering.jpg)

  ### Hierarchical Dendrogram
  The Ward's Linkage method used to justify the selection of three distinct clusters.
  ![Dendrogram](Dendrogram.jpg)

  # Elbow Graph
![Dendrogram](elbow.jpg)

# Statistical Distribution (Boxplots)
![Boxplots](visualisations.jpg)

</details>

Data ETL: Extraction of 3 years of market data using the Yahoo Finance API.
Feature Engineering: Calculation of financial risk metrics and data normalization using StandardScaler.
Clustering Analysis: Agglomerative Hierarchical Clustering (Ward’s Linkage) to find natural groupings.
K-Means Clustering validated by Elbow Method and Silhouette Scores.
BI Integration: Proposed Star Schema for a Data Mart and a strategic report on CRM sustainability.

Key Visuals:
Dendrogram: Justifies the selection of N=3 clusters using Ward's linkage.

3D Risk Map: Visualizes how Cluster 2 (Aggressive) separates from the market core based on Beta.

Boxplots: Demonstrates the statistical "spread" of each group, confirming that Cluster 0 has the lowest variance.Language: Python 3.x (Google Colab)

BI Tools: 
Star Schema Design, CRM Sustainability Framework
