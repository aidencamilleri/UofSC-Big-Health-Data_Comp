
# Gene Expression Analysis Competition

## Overview

This project involves analyzing a dataset of 63,856 gene expressions from 4,000 patients to identify patterns related to a specific ailment. My team has implemented a series of data processing, dimensionality reduction, clustering, and classification techniques to achieve this goal.

## Project Structure

- **Data Cleaning**: Verified no duplicates or null values, ensured consistent data types, and transposed the dataset.
- **Feature Reduction**: Reduced the number of genes from ~63,000 to 683 by removing genes with a range of expressions less than five.
- **Dimensionality Reduction**: Applied PCA to reduce dimensions from 683 to 50, followed by t-SNE to reduce to 2 dimensions for visualization.
- **Clustering**: Used K-Means clustering to classify patients into two groups.
- **Gene Importance**: Trained a random forest classifier to identify the most important genes related to the ailment.

## Results

The analysis identified a pattern related to coronary disease, with key genes including ENSG00000004776.12, ENSG00000138207.13, ENSG00000162407.8, ENSG00000170323.8, and ENSG00000115414.18.

## Acknowledgements

- **Team Members**: Bo Dwyer, Kyle Barretto, Jash Hyland
- **References**: Oskolkov, Nikolay. “How to Cluster in High Dimensions.” Medium, Towards Data Science, 30 July 2019.
