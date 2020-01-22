# ENIGMA-MDD-Obesity

## Abstract
Emerging evidence suggests that obesity impacts brain physiology at multiple levels. Here we aimed to clarify the relationship between obesity and brain structure using structural MRI data from the ENIGMA Major Depressive Disorder (MDD) working group. Obesity (BMI>30) was significantly associated with cortical and subcortical abnormalities in mass-univariate analyses independent of MDD diagnosis. We complemented the applied mass-univariate testing approach by conducting pattern recognition analyses to investigate multivariate patterns of brain structural differences between obese and normal weight subjects. To this end, a machine learning pipeline consisting of several preprocessing steps including imputation of missing values, dimensionality reduction by principal component analysis and random undersampling and a support vector machine was trained on all available 157 FreeSurfer derived imaging measures to individually classify participants as either obese or normal-weight using pooled multisite nested cross validation employing the PHOTON framework  (https://photon-ai.com). Multivariate pattern classification analyses further confirmed the relationship between obesity and brain structure by yielding highly significant single-subject differentiation between obese  and normal-weight subjects with a balanced accuracy rate of 68.7%. Similar results were observed when analyses were performed in samples of obese and normal weight subjects that were balanced for age, sex and MDD diagnosis. Analyses employing leave-one-site-out-cross-validation including all sites with a minimum n>50 in each group yielded a lower but still highly significant accuracy rate. Our findings suggest a neurobiological interaction between obesity and brain structure under physiological and pathological brain conditions.

## Software
The machine learning analysis is coded in PHOTON, a high-level Python API designed to simplify and accelerate the process of machine learning model development. It is specifically designed for the demands of scientific use cases, integrating different data modalities, enabling rapid design iterations and ensuring unbiased model performance estimations whilst adhering to the field's current best practices. For more information see [www.photon-ai.com](www.photon-ai.com)

## Scripts


