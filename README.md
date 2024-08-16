# Data-Leakage-in-Predicting-Infant-Growth-Outcomes
Predictive modeling using machine learning (ML) holds promise for identifying and managing the developmental risks associated with Small-for-Gestational-Age (SGA) infants, defined by birth weights below the 10th centile. However, the integrity of these models is often compromised by data leakage, which can significantly distort validation outcomes.

Our research highlights the subtle but profound ways in which data leakage can undermine the validity of predictive modeling in medical applications. By underscoring the importance of stringent data management practices, this project aims to advance the development of more reliable ML models for predicting SGA infants.

Please note that specific results cannot be displayed, but our findings raise critical concerns about data leakage in medical ML research.

# Coding:
**File**: dataleakage_infantsgrowthoutcome.ipynb
**input**: df_tri2_12w28w_drop_death_train_bw.csv
**output**: /evaluation/...csv
**Description**:
This Jupyter Notebook provides an in-depth exploration of data leakage issues within the context of a specific dataset. The notebook presents various experimental designs to illustrate how different approaches can lead to data leakage, which may compromise the validity of machine learning models. The experiments cover several critical aspects, including:

- Resampling: Examining the impact of oversampling or undersampling on data leakage.
- Imputation: Investigating how different methods of handling missing data can introduce leakage.
- Normalization: Assessing the effect of applying normalization techniques on both the training and testing sets.
- Feature Selection: Analyzing the risks of selecting features based on the entire dataset instead of solely the training set.
- Duplicates in Datasets: Identifying the presence and consequences of duplicate records within the data.
- Illegitimate Features: Exploring how the inclusion of features that are not legitimate can skew model performance.
- Non-Independent Training and Testing Sets: Highlighting the dangers of non-independence between the training and testing sets, which can lead to overly optimistic results.

The goal of this notebook is to provide a clear understanding of the subtle and often overlooked ways in which data leakage can occur, emphasizing the importance of careful experimental design and data management in machine learning applications.
