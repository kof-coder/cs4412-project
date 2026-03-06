# CS 4412 — Data Mining Project

**Course:** CS 4412 Data Mining  
**Module:** M2 Initial Implementation  
**Author:** Kofi Ofori-Acquah  

## Project Summary

In this project, the researcher aims to investigate the techniques of managing fatigue using data mining techniques. The techniques of managing fatigue will be analyzed using techniques of **Exploratory Data Analysis, Preprocessing, Feature Engineering, and K-Mean Clustering**.

**Dataset Size:** 500 rows * 11 attributes  
**Technique Used for Mining:** K-Mean Clustering  

**Project Title:** Discovery of Short-Term Fatigue Management Techniques (Power Naps and Coffee)  

---

## Project Goal

The overall goal of the project is to discover the techniques of managing fatigue using data mining techniques. This is not a prediction problem. In this project, the overall goal is to discover the techniques of managing fatigue using power naps and coffee.  

---

## Dataset

In this project, the researcher uses a dataset of **size 500 rows * 11 attributes**. The attributes of the dataset are as follows:  
sleep_hours_previous_night  
intervention_type  
intervention_duration_minutes
* alertness_before  
* alertness_after  
* productivity  
* mood  
* side_effects  

The dataset is related to the management of fatigue, and each row represents a session in the management of fatigue.

---

## Project Structure

### data/raw
The raw data.

### data/processed
The clean data and clustered data used in the mining process.

### notebooks
The Jupyter notebook used in the implementation.

### outputs
The cluster profile and results obtained in the mining process.

### docs
The project summary.

---

## Mining Technique Used

**K-MEANS Clustering**

The steps followed in the mining process:
1. Data preprocessing  
2. Feature engineering  
3. Standardization  
4. Silhouette method  
5. K-MEANS Clustering  
6. Cluster interpretation  

---

## Key Insight Example

The initial results obtained show that power naps have positive effects on improving alertness compared to the effect of coffee, though they have similar effects on productivity and moods.

---

## Future Work (M3)

* Association mining  
* Anomaly detection  
* PCA visualization  
* Comparison of other clustering techniques
