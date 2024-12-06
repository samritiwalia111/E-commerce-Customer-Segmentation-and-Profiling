# E-commerce Customer Segmentation and Profiling

## Project Overview
This project segments e-commerce customers based on **Recency**, **Frequency**, and **Monetary** (RFM) metrics. The goal is to identify distinct customer segments for targeted marketing strategies.

## Methodology
We applied **KMeans clustering** to segment customers and then used **Principal Component Analysis (PCA)** to visualize the segmentation. We evaluated the model's performance using the **Silhouette Score** and **Davies-Bouldin Index**.

### Steps:
1. **Data Preprocessing**: Cleaned and transformed raw data (handling missing values, outliers, and date conversion).
2. **Segmentation**: Performed customer segmentation using **KMeans** based on RFM metrics.
3. **Evaluation**: Used **PCA** for dimensionality reduction and **Silhouette Score** and **Davies-Bouldin Index** for model evaluation.

## Visualizations

### 1. Elbow Method for Optimal Clusters
The Elbow Method plot helps determine the optimal number of clusters for customer segmentation.
![Elbow Method](images/Elbow Method for Optimal K.png)
### 2. 2D PCA Scatter Plot
A 2D PCA scatter plot visualizing customer segments.
![PCA 2D Scatter](images/pca_2d_scatter.png)

### 3. 3D Customer Segments
A 3D plot of the customer segments based on Recency, Frequency, and Monetary metrics.
![Customer Segment 3D](images/customer_segment_3d.png)

### 4. Correlation Heatmap for RFM Metrics
Correlation heatmap showing how Recency, Frequency, and Monetary metrics relate to each other.
![Correlation Heatmap](images/correlation_heatmap.png)

### 5. Recency Distribution Boxplot
Boxplot showing the distribution of Recency across customer segments.
![Recency Boxplot](images/recency_boxplot.png)

### 6. Frequency, Monetary, and Recency Distribution Boxplots
Boxplots showing the distribution of Frequency, Monetary, and Recency across customer segments.
![Frequency, Recency, and Monetary Boxplot](images/frequency_monetary_boxplot.png)

### 7. Frequency, Recency, and Monetary Distribution Histograms
Histograms showing the distribution of Frequency, Recency, and Monetary across customer segments.
![Frequency, Recency, and Monetary Histograms](images/frequency_recency_monetary_histogram.png)

### 8. Pairplot of Recency, Frequency, and Monetary
A pairplot of Recency, Frequency, and Monetary for visualizing relationships between the three metrics.
![Pairplot](images/pairplot_recency_frequency_monetary.png)

## Requirements

- pandas
- numpy
- matplotlib
- seaborn
- sklearn

## Conclusion
This project helps businesses better understand their customer base and apply targeted marketing strategies based on customer segmentation.
