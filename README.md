# Socioeconomic Clustering of Mexican States Using ENIGH 2022

## Overview

This project applies dimensionality reduction and hierarchical clustering techniques to identify socioeconomic patterns among Mexican states using data from the National Household Income and Expenditure Survey (ENIGH) 2022.

The objective is to uncover groups of states with similar socioeconomic characteristics and explore how unsupervised learning can support evidence-based decision-making in public policy, insurance, and socioeconomic analysis.

---

## Dataset

The analysis uses data from ENIGH 2022, published by INEGI.

The dataset contains indicators related to:

- Household income
- Household expenditure
- Education
- Health-related expenses
- Demographic characteristics
- Living conditions

---

## Objectives

- Explore socioeconomic differences among Mexican states.
- Reduce dataset dimensionality while preserving relevant information.
- Identify clusters of states with similar socioeconomic profiles.
- Interpret the resulting segments and evaluate potential applications.

---

## Methodology

The project follows the following workflow:

1. Data acquisition and preprocessing.
2. Exploratory Data Analysis (EDA).
3. Feature normalization and preparation.
4. Dimensionality reduction using Singular Value Decomposition (SVD).
5. Hierarchical clustering.
6. Cluster visualization and interpretation.
7. Socioeconomic profiling of the identified groups.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- SciPy
- Matplotlib
- Seaborn

---

## Results

The analysis identified groups of Mexican states sharing similar socioeconomic characteristics.

Hierarchical clustering revealed meaningful regional patterns associated with income, expenditure, education, and healthcare-related variables.

The dimensionality reduction process showed that a smaller number of latent factors retained most of the information contained in the original dataset, facilitating interpretation and visualization.

---

## Business Insights

### Insurance and Risk Assessment

The identified socioeconomic groups may help insurance companies better understand regional differences in healthcare expenditures and potential risk profiles.

### Public Policy

Government institutions can leverage these segments to design targeted social programs and allocate resources more efficiently.

### Market Analysis

Businesses may use regional segmentation to identify consumer groups with similar socioeconomic characteristics and tailor products or services accordingly.

### Resource Allocation

The clustering results provide a framework for prioritizing investments in healthcare, education, and infrastructure according to regional needs.

---

## Conclusions

The project demonstrates how dimensionality reduction and hierarchical clustering can transform complex socioeconomic datasets into interpretable and actionable information.

The identified clusters reveal that Mexican states exhibit distinct socioeconomic profiles that can be analyzed using unsupervised learning techniques.

These findings highlight the value of data-driven approaches for understanding regional disparities and supporting strategic decision-making across multiple sectors.

---

## Future Work

Potential extensions of this project include:

- Comparing results with K-Means and DBSCAN.
- Incorporating geospatial information.
- Evaluating cluster stability through resampling techniques.
- Building interactive dashboards for cluster exploration.

---

## Author

Abraham Nava

Data Science and Physics Student at UNAM

Machine Learning, Statistics, Mathematical Modeling, Data Analysis, and Data-Driven Decision Making.
