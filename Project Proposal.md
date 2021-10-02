# Project Proposal

## Introduction

Cancer is one of the major killers threatening human health and life, and the breast cancer has the highest incidence and mortality rate worldwide [1]. It is of great significance to identify novel and effective strategies for breast cancer diagnosis. In recent years, artificial intelligence (AI) technologies have played significant roles in the clinical care of breast cancer, providing new auxiliary approaches for clinicians to identify high-risk patients.

This project aims to classify benign and malignant tumors with the Breast Cancer Wisconsin Dataset, assisting physicians in diagnosis.

## Dataset and Project Goal

The dataset is from Breast Cancer Wisconsin (Diagnostic) Dataset [2], including 569 samples with 32 attributes each. Features are computed from digitized images of fine needle aspirate (FNA) of breast masses.

We try to develop an algorithm that can classify benign and malignant tumors based on the patient's physical condition, pathological characteristics of the tumor. In data pre-processing, we will analyze the features through data visualization and evaluate data quality for integrity, comprehensiveness, legality, and uniqueness. The PCA algorithm is likely to be utilized to rank and select important features.

In the classification part, support vector machine (SVM) and random forest (RF) will be applied as potential models. For SVM, we try to test different kernel functions, like linear kernel and nonlinear kernel (Gaussian kernel). RF is widely used in the medical field, as its good interpretability. We will adjust the number of decision trees and change the combination of features to train the different trees.

In terms of model evaluation, we refer to accuracy, precision and recall metrics of the models. P-R and ROC curves will also be plotted to compare models’ performance.

## Project Motivation

Data-driven methods are transforming the practice of medicine. It’s helping doctors diagnose patients more accurately. In practice, there are also many hospitals and medical institutions experimenting with medical AI approaches. Prediction of breast cancer diagnosis should be of value in both theoretical research and actual practice.

Technically, this project will involve modeling dataset, including cleaning, and analyzing features, as well as training and testing the model, which tend to be a significant application of what we learned in this course, and we could gain better skill in data processing.

## Reference

[1] Sung, H., Ferlay, J., Siegel, R. L., Laversanne, M., Soerjomataram, I., Jemal, A., & Bray, F. (2021). Global cancer statistics 2020: GLOBOCAN estimates of incidence and mortality worldwide for 36 cancers in 185 countries. CA: A Cancer Journal for Clinicians, 0(0), 1–41. https://doi.org/10.3322/caac.21660

[2] https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29 











