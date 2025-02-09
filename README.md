# Mall Customer Segmentation Analysis

## Project Description

This project implements customer segmentation analysis on mall customer data using various clustering techniques. The analysis aims to help retail businesses better understand their customer base by identifying distinct customer groups based on demographic and behavioral factors such as age, annual income, and spending patterns.
Features

Comprehensive data analysis including univariate, bivariate, and multivariate analysis
Multiple clustering approaches (K-means clustering):

Univariate clustering based on annual income
Bivariate clustering using income and spending scores
Multivariate clustering incorporating age, income, spending score, and gender

Detailed visualization of customer segments using seaborn and matplotlib
Gender-based analysis of shopping patterns
Correlation analysis between different customer attributes

## Visualizations

### Customer Segments
![Image](https://github.com/user-attachments/assets/22b89bc6-8aec-476f-afdc-68b5182ac5ad)
- Figure 1: Customer segments based on Income and Spending Score*

### Correlation Heatmap
![Image](https://github.com/user-attachments/assets/240f692b-3922-4db1-8f3c-47f030240e21)
- Figure 2: Correlation matrix of customer attributes*

### Income Distribution by Gender
![Image](https://github.com/user-attachments/assets/8cc7b144-73af-4988-b9c9-9836a2d6e29a)
- Figure 3: Distribution of annual income across genders*

### Optimal Number of Clusters
![Image](https://github.com/user-attachments/assets/9756dff9-6d21-4e0d-adc4-35d85f81c966)
- Figure 4: Elbow curve for determining optimal number of clusters*

## Results and Insights
### Customer Demographics

- Gender distribution: 56% Female, 44% Male
- Average age: ~39 years
- Average annual income: $60.56k
- Average spending score: 50.2 out of 100

## Key Findings

- Income-Based Segments (3 clusters):

- Lower income group (74 customers): Average income ~$33.5k
- Middle income group (90 customers): Average income ~$67.1k
- High income group (36 customers): Average income ~$99.9k

Income-Spending Based Segments (5 clusters):

- Cluster 0: Average spenders with moderate income (~$55.3k, spending score 49.5)
- Cluster 1: Low spenders with low income (~$26.3k, spending score 20.9)
- Cluster 2: High spenders with low income (~$25.7k, spending score 79.4)
- Cluster 3: Low spenders with high income (~$88.2k, spending score 17.1)
- Cluster 4: High spenders with high income (~$86.5k, spending score 82.1)


## Notable Insights

- Age shows a negative correlation (-0.327) with spending score.
- No significant correlation between income and spending patterns (0.009).
- Female customers show slightly higher spending scores (51.5) compared to male customers (48.5).
- Younger customers (around age 25) tend to have higher spending scores regardless of income.
- High-income clusters show more gender balance compared to other segments.

### Technologies Used

- Python
- Pandas
- Scikit-learn (K-means clustering)
- Seaborn
- Matplotlib
- StandardScaler for data preprocessing

This analysis provides valuable insights for targeted marketing strategies, inventory planning, and customer relationship management in retail settings.


