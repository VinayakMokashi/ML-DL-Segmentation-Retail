# ML/DL-Driven Customer Segmentation for Enhanced Retail Marketing Strategies

This project leverages machine learning (ML) and deep learning (DL) techniques to perform customer segmentation based on purchasing behaviors in a retail setting. By dividing customers into distinct groups, marketers can tailor strategies to specific customer needs, driving targeted marketing and increasing revenue.

## Project Overview:

The objective of this project is to create a targeted marketing strategy for a retail company by categorizing customers into meaningful segments based on their buying behaviors. Through data science techniques, we can analyze customer data to better understand purchasing habits and ultimately drive more effective marketing campaigns.

## Features and Goals:

__Data Cleaning & EDA__: Standardizing data, identifying relationships between features, and preparing it for analysis.

__Dimensionality Reduction__: Using Autoencoders and PCA to reduce the feature space, making clustering more effective.

__Customer Segmentation__: Grouping customers using K-means clustering for targeted marketing.

__Visual Analysis__: Interactive 3D visualization to explore the distinct segments created.

## Project Workflow:

__Data Preprocessing and Exploration__:

Perform data cleaning to handle null values and ensure consistency.

Use exploratory data analysis (EDA) to gain insights into customer data.

Apply correlation analysis to identify key variables impacting segmentation.

__Dimensionality Reduction__:

Autoencoders: Implemented with TensorFlow, these neural networks reduce data dimensionality while preserving critical features.

PCA (Principal Component Analysis): Applied using Scikit-Learn to further simplify data and prepare for visualization.

__Clustering with K-means__:

Elbow Method: Determines the optimal number of clusters by measuring the Within-Cluster Sum of Squares (WCSS).

K-means Clustering: Segments customers into distinct groups based on purchasing behaviors, creating actionable clusters.

__Visualization__:

3D Plotting with Plotly: Visualizes customer segments in 3D, enabling marketers to intuitively explore clusters and develop targeted campaigns.

## Project Structure:

__sales_data_sample.csv__: Dataset used for analysis

__Code_Marketing.ipynb__: Colab Notebook/Code File

__autoencoder.h5__: Stored model weights

## Detailed Steps:

### Data Preprocessing:

Load data, handle missing values, and normalize features using StandardScaler.

Conduct exploratory analysis to understand patterns in the data.

### Dimensionality Reduction:

Autoencoders: Use a deep neural network to encode data into a compressed representation, reducing redundancy.

PCA: Applied to the encoded data to capture key features in three dimensions, facilitating easy visualization.

### Optimal Clustering (K-means with Elbow Method):

Use the Elbow Method to plot WCSS against various values of k to determine the optimal number of clusters.

Apply K-means clustering to create customer segments based on the purchasing patterns.

### Visualization:

Use Plotly to create an interactive 3D scatter plot of clusters, which helps in gaining insights and exploring the segmentation effectively.

## Results:

The segmentation revealed distinct groups of customers, allowing marketers to create targeted campaigns for each segment. Each cluster represents a unique set of purchasing behaviors, aiding in personalized marketing strategies.

## Technologies Used:
__Python__: Programming language for data processing and machine learning.

__Pandas & Numpy__: Data manipulation and analysis.

__TensorFlow__: Building Autoencoders for dimensionality reduction.

__Scikit-Learn__: Implementing K-means clustering, PCA, and scaling.

__Plotly__: 3D visualizations for exploring clusters interactively.

__Matplotlib & Seaborn__: EDA and data visualization.

## Future Enhancements:

__Incorporate Other Clustering Techniques__: Experiment with hierarchical clustering or DBSCAN for further segmentation insights.

__Advanced Deep Learning__: Explore variational autoencoders (VAEs) to improve feature extraction.

__Automated Marketing Insights__: Integrate clustering results with real-time marketing automation platforms.

__Expand Visualization__: Create dashboard-style visuals for continuous data exploration and reporting.
