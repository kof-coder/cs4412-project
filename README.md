# CS 4412 — Data Mining Project
## Module 2: Initial Implementation

**Author:** Kofi Ofori-Acquah

---

## Project Title

**Discovery of Short-Term Fatigue Management Techniques (Power Naps and Coffee)**

---

## Project Goal

The main goal of this project is to discover patterns in the management of fatigue using data mining techniques. It is not a prediction problem. In this project, the main aim is to discover the effects of power naps and coffee on the management of fatigue.

---

## Dataset

The dataset used in this project has **500 rows and 11 columns**, with the following attributes:

* sleep_hours_previous_night  
* intervention_type  
* intervention_duration_minutes  
* alertness_before  
* alertness_after  
* productivity  
* mood  
* side_effects  

The dataset is about the management of fatigue, and each row in the dataset is a single session in the management of fatigue.

---

## Project Structure

### data/raw
The raw data.

### data/processed
The cleaned data and the clustered data used in the mining process.

### notebooks
The Jupyter notebook used in the implementation.

### outputs
The cluster profile and results obtained in the mining process.

### docs
The project summary.

---

## Mining Technique Used

**K-Means Clustering**

The steps followed in the mining process are as follows:

1. Data preprocessing  
2. Feature engineering  
3. Standardization  
4. Silhouette method  
5. K-Means Clustering  
6. Cluster interpretation  

---

## Key Insight Example

The initial results obtained indicate that power naps are effective in improving alertness compared to the effects of coffee, although the effects on productivity and moods are similar.

---

## Future Work (M3)

* Association mining  
* Anomaly detection  
* PCA visualization  
* Comparison of other clustering techniques
