# Marketing Campaign Analysis and Customer Segmentation

## Overview
This project aims to analyze a marketing campaign dataset and perform customer segmentation using various data preprocessing and clustering techniques. The dataset includes information about customer demographics, their purchases, and their response to different marketing campaigns. The goal is to segment customers into distinct groups for targeted marketing strategies.

## Dataset
The dataset used in this project is the "marketing_campaign.csv" file. It includes detailed information about customers, their demographics, purchase history, and responses to marketing campaigns.

## Project Structure
The project is divided into the following steps:

1. **Data Loading and Initial Exploration**: Load the dataset and explore the initial structure and summary statistics.
2. **Data Cleaning and Preprocessing**: Handle missing values, convert date formats, and engineer new features.
3. **Feature Transformation**: Label encode categorical variables and scale numerical features.
4. **Dimensionality Reduction**: Use PCA to reduce the number of features to three principal components.
5. **Clustering**: Apply the K-means clustering algorithm and determine the optimal number of clusters using the elbow method.
6. **Visualization**: Visualize the data in 3D space and plot the correlation matrix.

## Requirements
- Python 3.7+
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- yellowbrick

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/marketing-campaign-analysis.git
    cd marketing-campaign-analysis
    ```

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter notebook to execute the analysis:
    ```bash
    jupyter notebook
    ```
4. Open `marketing_campaign_analysis.ipynb` and run the cells sequentially.

## Results
- **Feature Engineering**: Created new features to enhance the analysis.
- **Dimensionality Reduction**: Reduced the feature space to three principal components using PCA.
- **Clustering**: Determined the optimal number of clusters using the elbow method and applied K-means clustering.

## Conclusion
This project demonstrates the process of data cleaning, feature engineering, scaling, dimensionality reduction, and clustering. The resulting customer segments can be used for targeted marketing strategies, potentially improving the effectiveness of marketing campaigns.
