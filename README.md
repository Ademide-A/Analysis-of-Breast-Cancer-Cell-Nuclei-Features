# Analysis-of-Breast-Cancer-Cell-Nuclei-Features

Aim/Hypothesis

Aim: The primary aim of this project is to analyse the characteristics of cell nuclei from breast cancer tissue samples to distinguish between malignant and benign tumours.

Hypothesis: Specific features of cell nuclei, such as radius, texture, perimeter, and area, significantly differ between malignant and benign tumours, allowing for their classification based on these features.

Key Stakeholders
- Medical Researchers: Interested in understanding the distinguishing features of malignant and benign tumours.
- Oncologists: Use the findings to enhance diagnostic accuracy.
- Data Scientists: Develop and validate models for cancer diagnosis.
- Healthcare Providers: Implement diagnostic tools based on this analysis.
- Patients: Benefit from improved diagnostic procedures.

Step-by-Step Process
1.	Data Collection: Acquired the dataset containing features of cell nuclei from digitised images of fine needle aspirate (FNA) of breast masses.
2.	Data Preparation:
o	Loaded the dataset.
o	Defined column names based on the feature information provided.
o	Split the data into benign and malignant categories.
3.	Descriptive Statistics:
o	Calculated average values, ranges, and percentages for key features.
4.	Correlation Analysis:
o	Encoded the diagnosis for correlation analysis.
o	Identified features highly correlated with the diagnosis.
5.	Visualisation:
o	Created histograms to compare the mean radius distributions for benign and malignant tumours.
o	Generated box plots to compare mean texture between the two classes.
6.	Statistical Tests:
o	Performed a t-test to determine the statistical significance of differences in mean perimeter between benign and malignant tumours.
7.	Results Compilation:
o	Summarised key findings, correlations, and significant differences.

Results and Findings
- Average Radius: Malignant tumours have a significantly higher average radius (17.46) compared to benign tumours (12.15).
- Range of Mean Area: Malignant tumours have a wider range (361.6 to 2501.0) than benign tumours (143.5 to 992.1).
- Class Distribution: 62.74% of the cases are benign, while 37.26% are malignant.
- Top Correlated Features with Diagnosis: worst_concave_points (0.79), worst_perimeter (0.78), and mean_concave_points (0.78) are highly correlated with the diagnosis.
- Highly Correlated Feature Pairs: Several feature pairs show high correlation, indicating potential redundancy.
- Statistical Significance: The mean perimeter difference between benign and malignant tumours is statistically significant (p-value = 1.02e-66).

Challenges Faced
- Data Understanding: Interpreting the medical significance of various cell nucleus features.
- Feature Correlation: Managing highly correlated features that could indicate redundancy, complicating the analysis.
- Visual Representation: Ensuring clear and informative visualisations for stakeholders from diverse backgrounds.

Future Enhancements
- Advanced Modelling: Implement machine learning models to classify tumours based on these features.
- Feature Engineering: Explore additional features or combinations of features that could improve classification accuracy.
- Clinical Validation: Collaborate with medical professionals to validate findings and integrate them into clinical practice.
- Automated Diagnostics: Develop automated diagnostic tools based on the analysis for real-time use in clinical settings.
- Longitudinal Studies: Analyse changes in features over time to understand tumour progression.

This analysis has provided valuable insights into the distinguishing characteristics of benign and malignant tumours, offering a foundation for improved diagnostic methods and future research.
