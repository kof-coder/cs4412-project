# CS 4412 - Data Mining Project

**Course:** CS 4412 Data Mining  
**Current milestone:** M3 Complete Implementation  
**Author:** Kofi Ofori-Acquah  

## Project Summary

This project studies fatigue, sleep quality, and lifestyle patterns using data mining for **discovery**, not prediction.  
The M2 work explored a simulated fatigue-management dataset, while M3 expands the project using a **real-world sleep and lifestyle dataset** to produce stronger and more realistic findings.

The current M3 implementation includes:
- clustering comparison (**K-Means, Agglomerative, DBSCAN**)
- **PCA** for low-dimensional visualization
- **Decision Tree** and **Naive Bayes** for interpretable class analysis
- **association rules** for co-occurrence patterns
- **LOF anomaly detection** for unusual sleep-health profiles

## Datasets

### M2 dataset
- `data/raw/power_nap_vs_coffee_effectiveness_dataset.csv`
- Simulated fatigue-management sessions comparing power naps and coffee

### M3 dataset
- `data/raw/Sleep_health_and_lifestyle_dataset.csv`
- Real-world sleep and lifestyle records with demographics, occupation, stress, BMI, blood pressure, heart rate, steps, and sleep disorder labels

## Repository Structure

```text
cs4412-project/
├── README.md
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── outputs/
└── docs/
```

## M3 Techniques Used

1. Data cleaning and preprocessing  
2. Feature extraction from blood pressure  
3. Standardization of numeric variables  
4. Clustering comparison with silhouette scores  
5. PCA visualization support  
6. Decision Tree and Naive Bayes for interpretable classification  
7. Association-rule mining on discretized features  
8. LOF anomaly detection  
9. Result interpretation tied to discovery questions  

## Key M3 Findings

- The best **K-Means silhouette score** was **0.537** at **k = 6**
- **Agglomerative clustering** slightly outperformed K-Means with silhouette **0.540**
- **DBSCAN** identified dense local structure and a set of noise points
- **LOF** flagged **18 anomalies** for follow-up analysis
- The decision tree and Naive Bayes models both achieved very high agreement with the discovered K-Means labels on the held-out split

## M3 Deliverables in this Repository

- `notebooks/CS4412_M3_Complete_Implementation.ipynb`
- `docs/CS4412_M3_Analysis_Document.pdf`
- `outputs/association_rules_m3.csv`
- `outputs/clustering_method_comparison_m3.csv`
- `outputs/cluster_profile_numeric_m3.csv`
- `outputs/cluster_profile_categorical_modes_m3.csv`
- `outputs/lof_anomalies_m3.csv`
- `outputs/decision_tree_feature_importance_m3.csv`
- `outputs/pca_explained_variance_m3.csv`

## Notes

- M2 files were kept for continuity and comparison.
- M3 uses a real-world dataset to address the limitations of simulated data noted after M2.
