# CS 4412 - Data Mining Project

**Course:** CS 4412 Data Mining  
**Module:** M2 Initial Implementation  
**Author:** Kofi Ofori-Acquah  

## Project Summary

The project is based on the use of data mining techniques in the discovery of techniques used in the management of fatigue. The project is based on the discovery of the effects of **power naps and coffee on alertness, productivity, and moods** using techniques in exploratory data analysis, preprocessing, feature engineering, and **K-Means Clustering**.

The project is based on **discovery**, not prediction.

Dataset used in the project: **500 rows x 11 attributes**

The technique used in the project is **K-Means Clustering**.

## Project Title

**Discovery of Short-Term Fatigue Management Techniques - Power Naps and Coffee**

---

## Project Goal

The main aim of the project is to discover the patterns in the management of fatigue using the techniques of data mining. The project is not based on prediction. In this project, the main aim is to discover the effects of power naps and coffee in the management of fatigue.

---

## Dataset

The dataset used in the project contains **500 rows x 11 attributes** with the following attributes:

* sleep_hours_previous_night  
* intervention_type
* intervention_duration_minutes
* alertness_before  
* alertness_after  
* productivity  
* mood  
* side_effects  

The data is related to the management of fatigue, and each entry in the data is related to a session of the management of fatigue.

---

## Project Structure

### data/raw
The raw data is kept here.

### data/processed
The processed data and the clustered data used in the mining process are kept here.

### notebooks
The Jupyter notebook related to the implementation is kept here.

### outputs
The cluster profile and results obtained in the mining process are kept here.

### docs
The summary of the project is kept here.

---

## Mining Technique Used

**K-MEANS CLUSTERING**

The steps involved in the mining process are as follows:

1. Data preprocessing  
2. Feature engineering  
3. Standardization  
4. Silhouette method  
5. K-MEANS CLUSTERING  
6. Cluster interpretation  

---

## Key Insight Example

The results obtained show that power naps are effective in improving alertness compared to the effect of coffee, although the effect of both is similar on productivity and moods.

---

## Future Work (M3)

* Association mining  
* Anomaly detection  
* PCA visualization  
* Comparison of other clustering techniques
