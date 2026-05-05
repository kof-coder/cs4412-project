Final Deliverables for M4 Milestone
This repository represents the final deliverables for M4, focusing on professional representation, reproducibility, and critical assessment.
Final Deliverables
•	reports/CS4412_Kofi_Ofori_Acquah_M4_Final_Report.pdf 
•	slides/CS4412_Kofi_Ofori_Acquah_Presentation.pdf 
•	video/CS4412_Kofi_Ofori_Acquah_Presentation.mp4 (or link if hosted externally) 
________________________________________
Discovery Questions (Final)
1.	What natural sleep-health segments exist in the dataset? 
2.	Which features distinguish those segments? 
3.	Which profiles are anomalous compared to similar individuals? 
________________________________________
Final Findings Summary
•	Clustered and found 6 distinct lifestyle-health segments 
•	Key differentiators: systolic blood pressure, heart rate, stress level, physical activity 
•	PCA preserved ~70% variance 
•	Found ~5% anomalous profiles (~18 records) via LOF 
•	Used Decision Tree to extract explainable rules 
________________________________________
How to Run This Project
1.	Install dependencies: 
pip install -r requirements.txt
2.	Launch Jupyter: 
jupyter notebook
3.	Run: 
notebooks/CS4412_M3_Complete_Implementation.ipynb
________________________________________
Critical Assessment (Summary)
Validity
•	Structure of discovered clusters backed by K-Means and Agglomerative clustering 
•	PCA visualization backed results 
•	Results appear valid but aren’t conclusive 

Limitations
•	Unsupervised learning: no labeled ground truth 
•	Dependent on preprocessing and parameters 
•	Observational study design → association, not causation 
•	Moderate size of dataset → generalizability concerns 
________________________________________
Ethical Considerations
•	Sleep and health data must be treated
• Findings cannot be applied in making medical decisions
•	Possibility of bias among occupational/lifestyle categories 
•	Best application: generating knowledge, not personal opinions
_________________________________________
Future Directions
•	Clearer semantic interpretation of clusters  
•	Further validation on bigger data sets 
•	Conduct anomaly detection analysis  
•	Examine longitudinal sleep trends 
___________________________________________
Miscellaneous
•	M2 files kept for consistency reasons 
•	M4 file denotes the final, portfolio-quality document
