Final Deliverables for M4 Milestone The following is the complete collection of deliverables pertaining to the M4 milestone in terms of professional representation, reproducibility, and critical evaluation. 

Final Deliverables 
• reports/CS4412_Kofi_Ofori_Acquah_M4_Final_Report.pdf 
• slides/CS4412_Kofi_Ofori_Acquah_Presentation.pdf 
• video/CS4412_Kofi_Ofori_Acquah_Presentation.mp4 (or link if stored outside the repo)

Discovery Questions (Final)

What natural segments related to sleep health exist in the dataset?
What are the differences that characterize those segments?
Whose sleep and health profiles are outliers compared to people like them?
Final Discovery Question Answers 

Summary 
• Discovered six distinct lifestyle-health segments through clustering 
• Differentiating factors include systolic blood pressure, heart rate, stress, exercise frequency 
• ~70% variance retained through PCA analysis • ~5% outlier profiles identified using LOF (~18 records) 
• Decision Trees used for extraction of meaningful rules

How to Run This Project

Dependencies: pip install -r requirements.txt
To run: jupyter notebook, then notebooks/CS4412_M3_Complete_Implementation.ipynb
Critical Evaluation 

(Summary) Validity 
• Clustering structure supported by K-Means and Agglomerative clustering 
• Results supported through visualization via PCA • Results seem valid but not conclusive

Limitations 
• No ground truth due to unsupervised learning 
• Highly dependent on parameters and preprocessing 
• Observational study means only association rather than causation 
• Not sufficiently large dataset raises generalizability concerns

Ethical Considerations 
• Sleep and health data should be handled accordingly 
• Cannot apply findings in any medical decision making 
• Potential biases among occupations or lifestyle groups 
• Good use of findings is in generating information, not opinion

Further Research Directions 
• Semantic explanation of segments
• Validation on larger datasets 
• Outliers analysis 
• Longitudinal trends of sleep health patterns

Miscellaneous 
• M2-related files maintained for consistency 
• M4 is final portfolio-level document
