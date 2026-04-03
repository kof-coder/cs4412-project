# CS 4412 - Data Mining Project

**Course:** CS 4412 Data Mining  
**Current milestone:** M3 Complete Implementation  
**Author:** Kofi Ofori-Acquah  

## Project Summary

The project examines the aspects of fatigue, sleep quality, and lifestyle patterns using the concepts of data mining for **discovery**, not prediction.  
The project was based on a simulated fatigue management dataset during the M2 milestone. However, the M3 milestone expands the project using a **real-world sleep and lifestyle dataset** to produce stronger and more realistic results.  

The current implementation for the M3 milestone includes:
- clustering comparison (**K-Means, Agglomerative, DBSCAN**)
- **PCA** for low-dimensional visualization
- **Decision Tree** and **Naive Bayes** for interpretable class-based analysis
- **Association rules** for co-occurrence patterns
- **LOF anomaly detection** for unusual sleep health patterns

## Datasets

### M2 dataset
- `data/raw/power_nap_vs_coffee_effectiveness_dataset.csv`
- Simulated fatigue management sessions on the effectiveness of power naps versus coffee

### M3 dataset
- `data/raw/Sleep_health_and_lifestyle_dataset.csv`
- Real-world sleep health and lifestyle patterns with various attributes like demographics, occupation, stress, BMI, blood pressure, heart rate, steps, and sleep disorders

## Repository Structure

```text
cs4412-project/
├── README.md
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├──
└── docs/
### M3 Techniques Utilized

1. Data cleaning and preprocessing  
2. Feature extraction using blood pressure readings  
3. Standardization of numeric features  
4. Clustering method comparison using silhouette score  
5. PCA visualization support  
6. Decision Tree and Naive Bayes for classification  
7. Association rule mining using discretized features  
8. LOF for anomaly detection  
9. Interpreting results in relation to discovery questions  

### Key Findings from M3 Techniques Utilized

- The optimal value for K was found to be 6 with a K-Means silhouette score of 0.537.  
- Agglomerative clustering performed slightly better than K-Means with a 0.540 silhouette score.  
- Dense local structure was found using DBSCAN with a cluster of noise points.  
- 18 anomalies were found using LOF.  
- Decision Tree and Naive Bayes classification models were found to have very high agreement with K-Means cluster labels.  

### M3 Deliverables in this Repository

- `notebooks/CS4412_M3_Complete_Implementation.ipynb`
- `docs/CS4412_M3_Analysis_Document.pdf`
- `outputs/association_rules_m3.csv`
- `outputs/clustering_method_comparison_m3.csv`
- `outputs/cluster_profile_numeric_m3.csv`
- `outputs/cluster_profile_categorical_modes_m3.csv`
- `outputs/lof_anomalies_m3.csv`
- `outputs/decision_tree_feature_importance_m3.csv`
- `outputs/pca_explained_variance_m3.csv`

### Notes on Deliverables for M3

- Files from M2 were retained to ensure consistency.  
-
