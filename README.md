# Linear-Discriminant-Analysis-for-Recognising-Differences
Advanced Digital Image Processing, TU Delft, Q3, Group Project

# Repository Contents

- `main.m`: main script
- `report.pdf`: project report
- `getData.m`: loads the OASIS brain MRI dataset in one of four variants
- `classify_data.m`: classifies subjects as Alzheimer's or healthy using either a nearest-neighbour classifier or SVM on the LDA-projected data
- `BigData.m`:  an exploratory script for visualising the dataset
- `Results/`:  some results
  
# Summary

Applied a PCA-LDA framework to MRI brain scans to classify Alzheimer's disease through dimensionality reduction. Evaluated classification accuracy across different numbers of principal components using k-fold cross-validation, demonstrating potential for early diagnosis of neurodegenerative diseases.

# Requirements

- MATLAB R2024b
