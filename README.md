# CryptoClustering

                                                              Cryptocurrency Clustering Project


Overview:
 This project employs a range of Python libraries and machine learning techniques to analyze and cluster cryptocurrencies based on their price change percentages over various periods. By examining these changes over time frames such as 24 hours, 7 days, 14 days, 30 days, 60 days, 200 days, and 1 year, we aim to uncover patterns that might help categorize these assets based on their volatility and market behavior.

Data:
The dataset consists of three cryptocurrencies, denoted as PC1, PC2, and PC3. Each cryptocurrency has been analyzed for its price change percentage across several time frames:
24 hours
7 days
14 days
30 days
60 days
200 days
1 year

Methodology:

The analysis was conducted using Python 3.8.1 and Python libraries and methods:

Data Preparation:
Pandas: Used for data manipulation and analysis.
NumPy: Employed for numerical operations.

Feature Scaling:
StandardScaler: Standardized the features by removing the mean and scaling to unit variance, essential for the clustering algorithm's performance.

Dimensionality Reduction:
PCA (Principal Component Analysis): Reduced the dimensionality of the dataset to simplify the visualization and analysis while retaining the essence of the information.

Clustering:
KMeans: Applied to cluster the cryptocurrencies based on their scaled and transformed features. The number of clusters was determined based on the dataset's intrinsic properties.

Visualization:
Matplotlib: Created visualizations to illustrate the clustering results and the PCA-reduced feature spaces.

Results:
The clustering analysis revealed distinct groups among the cryptocurrencies based on their volatility and performance over the analyzed periods. Here is a brief overview:
PC1 demonstrated relative stability over the longer term, making it potentially more suitable for conservative investment strategies.
PC2 showed significant short to medium-term gains but with a decrease over the past year, indicating higher volatility and potential for speculative trading.
PC3 displayed high volatility with notable short-term gains and losses, suggesting a riskier investment.

Conclusion:
The cryptocurrency clustering project provides valuable insights into the behavior of different cryptocurrencies over time. Through the application of machine learning techniques and data visualization, we have categorized cryptocurrencies into clusters that reflect their market behavior and volatility. This analysis can aid investors in making informed decisions based on their risk tolerance and investment horizon.

Future Directions:
Future work may include the incorporation of more cryptocurrencies into the analysis, the exploration of alternative clustering algorithms, and the inclusion of additional features such as trading volume and market capitalization to enrich the analysis.
![image](https://github.com/pjpeters13/CryptoClustering/assets/71742689/11f44b81-9ed6-4754-a9f8-983256f61bc3)
