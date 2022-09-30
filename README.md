# Glioma Classifier
Project for 02620 Machine Learning for Scientists

## Contributors
- **Ketaki Ghatole** 
- **Arnav Gupta**  
- **Aditi Sarathy**   
- **Mirudhula Mukandan**  

## Description
Glioma is the most common cancer of the central nervous system and a leading cause of death due
to poor prognosis. The treatment of gliomas greatly depends on accurate tumor classification. The
mostly widely used WHO classification classifies gliomas into low grade (Astrocytoma, Oligodendroglioma) and
high grade (Glioblastoma) based on their cells of origin. lassifying gliomas to distinguish between the lethal
high grade glioblastoma and the low grade gliomas is an unmet need and incorrect classification can
greatly affect the treatment plan and its outcome. 

This project used publicly available gene expression data and clinical information for glioma from The Cancer Genome Atlas (TCGA). The dataset included
704 samples with around 60,000 features with seven class types.

## Workflow
This project aims to classify between the normal and glioma samples and glioma subtypes using
supervised machine learning models. 
1. Gaussian Naive Bayes (GNB) - Implemented from scratch
2. k-Nearest Neighbour (k-NN) - Implemented from scratch
3. Logistic regression (LR) - Implemented from scratch
4. Support Vector Machine (SVM) - binary and multi-class using packages

This project compares the performance of all four models for given data using a 5-fold Cross
Validation

## Results
1. High performance metrics observed for Glioma vs Control classification
2. Average performance on classification of the Glioma subtypes
3. Better performance observed in classifying benign vs malignant
4. Best results with SVM

## Final Report 
<object data="https://github.com/ArnavGuptaa/02620_ML_Project/blob/main/ML_project_report.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://github.com/ArnavGuptaa/02620_ML_Project/blob/main/ML_project_report.pdf">
        <p>Please download the PDF to view it: <a href="https://github.com/ArnavGuptaa/02620_ML_Project/blob/main/ML_project_report.pdf">Download PDF</a>.</p>
    </embed>
</object>
