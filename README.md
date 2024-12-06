# E-commerce Customer Segmentation and Profiling

## Project Overview
In this project, I focused on segmenting e-commerce customers based on **Recency**, **Frequency**, and **Monetary** (RFM) metrics. The goal was to uncover distinct customer segments to help businesses implement targeted marketing strategies. By understanding when customers last purchased, how often they buy, and how much they spend, businesses can identify high-value customers and optimize their marketing efforts.

## Methodology
I applied the **KMeans clustering** algorithm to group customers based on their RFM scores. After performing the segmentation, I used **Principal Component Analysis (PCA)** for dimensionality reduction and visualization. To ensure the segmentation was meaningful, I evaluated the model using the **Silhouette Score** and **Davies-Bouldin Index**.

### Steps Taken:
1. **Data Preprocessing**: I cleaned and transformed the raw data by handling missing values, outliers, and converting dates to a usable format. This ensured the data was ready for analysis.
2. **Segmentation**: I performed customer segmentation using **KMeans clustering**, segmenting customers based on their RFM scores to identify distinct groups.
3. **Evaluation**: I applied **PCA** for dimensionality reduction and visualization, and used **Silhouette Score** and **Davies-Bouldin Index** to assess the quality of the clustering.

## Visualizations

### 1. Elbow Method for Optimal Clusters
I used the **Elbow Method** to determine the optimal number of clusters for customer segmentation. The plot shows the point where adding more clusters doesn’t significantly improve the model’s performance.
![Elbow Method](images/Elbow_Method_for_Optimal_K.png)

### 2. 2D PCA Scatter Plot
A **2D PCA scatter plot** visualizing customer segments. The plot helps to understand how customers are grouped based on their RFM metrics.
![PCA 2D Scatter](images/Customer_Segments_(2D).png)

### 3. 3D Customer Segments
A **3D plot** showing customer segments based on **Recency**, **Frequency**, and **Monetary** metrics. This provides deeper insights into the spatial relationships between the clusters.
![Customer Segment 3D](images/Customer_Segments_(3D).png)

### 4. Correlation Heatmap for RFM Metrics
This **correlation heatmap** shows how the three metrics (Recency, Frequency, and Monetary) are related to each other. Understanding these relationships is crucial for interpreting customer behavior.
![Correlation Heatmap](images/Correlation_Heatmap_of_FM_Metrics.png)

### 5. Frequency, Monetary, and Recency Distribution Boxplots
I created separate **boxplots** for **Frequency**, **Monetary**, and **Recency** to show the distribution of each metric across customer segments. These visualizations help understand the central tendency and spread of each metric, highlighting outliers and skewed distributions.

#### Frequency Boxplot
Shows the distribution of purchase frequency across segments, helping identify whether customers are frequent or occasional buyers.
![Frequency Boxplot](images/Frequency_Distribution_by_Customer_Segment.png)

#### Monetary Boxplot
Displays how much money customers in each segment are spending, highlighting high-value customers.
![Monetary Boxplot](images/Monetary_Distribution_by_Customer_Segment.png)

#### Recency Boxplot
Shows the recency of customer purchases. This plot helps businesses identify segments of customers who have recently interacted with the brand versus those who need re-engagement.
![Recency Boxplot](images/Recency_Distribution_by_Customer_Segment.png)

### 6. Frequency, Recency, and Monetary Distribution Histograms
I created histograms to show the distribution of **Frequency**, **Recency**, and **Monetary** values across customer segments. These histograms provide insights into the frequency of customer purchases, the timing of purchases, and the monetary contribution of each segment.

#### Frequency Histogram
Visualizes how often customers make purchases. Peaks in the histogram show ranges of high purchase frequency, while skewness may indicate a few very frequent buyers.
![Frequency Histogram](images/Frequency_Distribution_by_Segment.png)

#### Recency Histogram
Displays how recent customer purchases are. This helps identify active customers and those who may need re-engagement strategies.
![Recency Histogram](images/Recency_Distribution_by_Segment.png)

#### Monetary Histogram
Shows the amount of money customers spend. A skewed distribution might indicate that a small proportion of customers contribute most of the revenue.
![Monetary Histogram](images/Monetary_Distribution_by_Segment.png)

### 7. Pairplot of Recency, Frequency, and Monetary
A **pairplot** of **Recency**, **Frequency**, and **Monetary** metrics shows the relationships between these variables. It provides insights into how these metrics interact and whether any of the metrics strongly correlate with each other.
![Pairplot](images/Pairplot_of_Recency_Frequency_and_Monetary_by_Segment.png)

## Requirements
The following Python libraries were used to perform the analysis:
- **pandas**: For data manipulation and cleaning.
- **numpy**: For numerical operations.
- **matplotlib**: For creating static, animated, and interactive visualizations.
- **seaborn**: For statistical data visualization.
- **sklearn**: For machine learning algorithms (e.g., KMeans clustering and PCA).

## Conclusion
This project provided valuable insights into customer segmentation, helping businesses better understand their customer base. By applying **KMeans clustering** and visualizing the data with **PCA**, I was able to uncover actionable customer segments that can be targeted with specific marketing strategies. This analysis empowers businesses to focus on high-value customers and improve customer retention.

---

### Personal Achievements:
- **Data Preprocessing**: Cleaned and transformed raw data, ensuring its readiness for analysis.
- **Segmentation**: Applied **KMeans clustering** to segment customers based on RFM scores, uncovering meaningful customer groups.
- **Visualization**: Created clear and informative visualizations to make the segmentation results easily interpretable.
- **Model Evaluation**: Evaluated the clustering model using **Silhouette Score** and **Davies-Bouldin Index**, ensuring the quality of the customer segments.

---

This **README** highlights both the technical steps and your personal contributions, making it clear to recruiters or employers what you accomplished and how you can apply these skills in future projects. Feel free to adjust any specific details to fit your preferences or add more insights into your contributions.
