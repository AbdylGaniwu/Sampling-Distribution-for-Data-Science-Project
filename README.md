# Diabetes Treatment Outcome - HbA1c Level (a measure of blood suger level) Analysis Using Sampling Distributions

### **Project Overview**
This project analyzes the effectiveness of diabetes treatment plans by evaluating changes in HbA1c levels (a measure of blood sugar levels) in patients. By applying the concept of sampling distributions, we generalize the average HbA1c change from a sample to estimate the treatment outcome in the larger population.

### **Objective**
The objective is to estimate the average HbA1c change and assess treatment effectiveness through a detailed analysis of a diabetes patient dataset using sampling distributions.

### **Contents of the Project**
1. **Data Import and Display**  
   Loading two datasets, `treatments.csv` and `treatments_cut.csv`, and displaying their content.

2. **Data Combination**  
   The datasets are combined into one to facilitate analysis.

3. **Data Assessment**  
   Reviewing the dataset for:
   - Number of rows
   - Data types and column details
   - Missing values

4. **Data Cleaning**  
   Filling missing values in the dataset to ensure consistency.

5. **Sampling and Analysis**  
   - A random sample of 30 patients is taken to analyze the HbA1c change.
   - Mean and standard deviation of the HbA1c change for the sample are calculated.

6. **Sampling Distribution**  
   A sampling distribution is created by taking 1,000 random samples and computing the mean HbA1c change for each sample.

7. **Visualization**  
   The sampling distribution of HbA1c changes is visualized using a histogram to demonstrate how sample means distribute around the population mean.

8. **Statistical Analysis**  
   Estimation of the population mean and standard error based on the sampling distribution.

9. **Confidence Interval Calculation**  
   A 95% confidence interval is calculated to provide a range in which the true mean HbA1c change lies.

10. **Results Summary**
   - **Mean HbA1c Change (Sample):** 0.5965
   - **Standard Deviation (Sample):** 0.2872
   - **Estimated Mean HbA1c Change (Population):** 0.5414
   - **Standard Error:** 0.06329
   - **95% Confidence Interval:** 0.4172 to 0.6656

### **Key Insights**
- This project highlights how sampling distributions can be effectively used in the medical field to generalize sample findings to the larger population.
- By monitoring the HbA1c change in diabetes patients, we can assess how effective the treatments are in lowering blood sugar levels.


### **Technologies Used**
- **Python Libraries:** pandas, numpy, seaborn, matplotlib, scipy
- **Statistical Methods:** Sampling Distributions, Confidence Intervals, Mean, Standard Deviation

### **Contributing**
If you'd like to contribute to this project, feel free to fork the repository and submit pull requests.

By using statistical methods, this project showcases how data science can contribute to medical research by providing insights into treatment outcomes.
