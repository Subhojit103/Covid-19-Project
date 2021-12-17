# Covid-19-Project
Classification of Covid-19 patients using high dimensional data reduction techniques with plasma proteomics dataset

The main objective of this project is to find out important proteins to classify Covid-19 patients with plasma proteomics data using high dimensional data reduction techniques.
The steps are as follows
1. Data cleaning, structural modifications & missing value treatments.
2. Outlier detection using box-plot, z-score and treatment using IQR.
3. Missing value imputation using KNN, mean, median
4. Normalization using Min-Max scaling, Standardization & Robust scaling.
5. Dimension reduction using SIS followed by LASSO with k-fold CV and random forest classification using shrunken centroid method and other methods.

Till now, I got 17 important proteins from 1500 proteins which are important to classify Covid-19 patients.
