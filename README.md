## Customer Segmentation Analysis
## Project Overview
This project implements an unsupervised machine learning approach to segment customers based on their purchasing behavior, demographic characteristics, and campaign responsiveness. Using a marketing campaign dataset from Kaggle, the analysis employs K-Means clustering and Principal Component Analysis (PCA) to identify distinct customer groups that can inform targeted marketing strategies.

## Project Goals
Perform comprehensive data preprocessing and feature engineering

Conduct exploratory data analysis to understand customer characteristics

Implement dimensionality reduction using PCA

Apply K-Means clustering to identify customer segments

Provide actionable insights for marketing optimization

## Dataset
The analysis uses the Marketing Campaign dataset from Kaggle, which contains information about 2,240 customers with 29 attributes including:

Demographic information (Age, Education, Marital Status, Income)

Purchasing behavior (various product categories)

Campaign responsiveness

Web and store visit patterns

Source: Kaggle Marketing Campaign Dataset

## Methodology
The project follows a structured approach across three milestones:

Milestone 1: Data Retrieval and Pre-processing
Environment setup and library installation

Data loading and initial exploration

Handling missing values and duplicates

Basic statistical analysis

Milestone 2: Feature Engineering
Creation of new features (Age, Accepted Campaigns, Total Items, Total Purchases)

Removal of irrelevant features

Outlier detection and treatment using IQR method

Comprehensive visualization of distributions and relationships

Milestone 3: K-Means Clustering and PCA
One-hot encoding of categorical variables

Data scaling using StandardScaler

Dimensionality reduction with PCA (3 components)

Determination of optimal clusters using the Elbow method

Implementation of K-Means clustering with 4 segments

3D visualization of customer segments

## Key Findings
Customer Segmentation
The analysis identified 4 distinct customer segments:

High-Value Responsive Customers: Higher income, more purchases, responsive to campaigns

Moderate Spenders: Average income and purchasing behavior

Budget-Conscious Customers: Lower income, fewer purchases, price-sensitive

Young Inactive Customers: Younger demographic, lower engagement

Behavioral Patterns
PhD holders show the highest purchase volumes among education levels

Campaign acceptance rates are generally low across all segments

Clear correlation between education level and purchasing behavior

Income distribution shows expected patterns with some outliers

Feature Importance
The PCA analysis revealed that the most significant factors driving segmentation are:

Income level and purchasing power

Campaign responsiveness

Product category preferences

Channel preferences (online vs. in-store)

## Technologies Used
Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Google Colab

## Installation & Usage
Clone or download the project files

Open the Jupyter Notebook in Google Colab

Ensure all required packages are installed

The dataset will be automatically downloaded from the provided URL

Run the cells sequentially to reproduce the analysis

## Results and Applications
The customer segmentation provides valuable insights for marketing strategy:

Targeted Campaigns: Different messaging for each segment based on their characteristics

Product Recommendations: Tailored suggestions based on segment preferences

Channel Optimization: Focus resources on channels preferred by high-value segments

Pricing Strategies: Segment-specific pricing and promotion approaches

## Acknowledgments
This project was completed as part of the National Student Data Corps (NSDC) Data Science Projects program. Special thanks to the project mentors and the NSDC team for their guidance and support.

## Contact
For questions about this project, please contact Natalia Garzón.

## License
This project uses open data from Kaggle. Please review the terms of use for the dataset before using this analysis for other purposes.
