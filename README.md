# FYP-Prediction-of-Mild-Cognitive-Impairment-and-Vascular-Risk-Factors

This project focuses on developing an intelligent multimodal framework for the early detection of Alzheimer's disease progression from Mild Cognitive Impairment (MCI). The project combines clinical data digitization, neuroimaging analysis, and machine learning to assist healthcare professionals in identifying patients at risk of developing Alzheimer's disease.

The proposed system integrates heterogeneous medical data sources, including handwritten clinical records, brain Magnetic Resonance Imaging (MRI), Positron Emission Tomography (PET) scans, neuropsychological assessments, demographic information, genetic markers, and vascular risk factors. By transforming these diverse data into structured representations and extracting meaningful biomarkers, the framework aims to support the differentiation between stable MCI (sMCI) patients and progressive MCI (pMCI) patients who are likely to develop Alzheimer's disease.

## Project Objectives

The project contributes to the development of AI-assisted tools for neurology by:

- Digitizing handwritten clinical records.
- Extracting structured medical information automatically.
- Identifying neuroimaging biomarkers associated with Alzheimer's disease.
- Investigating amyloid positivity and brain atrophy patterns.
- Integrating multimodal patient information into a unified framework.
- Supporting the prediction of Alzheimer's disease progression in MCI patients.

## Expected Outcomes
- Intelligent clinical data extraction system.
- Neuroimaging biomarker detection models.
- Multimodal Alzheimer's disease prediction framework.
- Research publications and scientific contributions.
- Software prototype to support neurologists in patient assessment and prognosis.

## What We Built

### 1. Clinical Data Digitization Pipeline

A complete pipeline was designed to convert handwritten neurological records into structured digital data:

Optical Character Recognition (OCR) for handwritten medical documents.
Fine-tuning and adaptation of OCR models using hospital records and the RIMES French handwritten dataset.
Natural Language Processing (NLP) techniques for extracting relevant clinical information from medical notes.
Structuring of extracted information for downstream machine learning applications.

### 2. Neuroimaging Biomarker Extraction

We developed imaging pipelines to identify biomarkers associated with Alzheimer's disease from MRI and PET scans.

- **MRI Analysis**

  - Automatic brain atrophy assessment using the Medial Temporal Lobe Atrophy (MTA) scale.
  - Development and evaluation of deep learning models for image-based atrophy classification.
  - Patient-level evaluation protocols and longitudinal data handling.

- **PET Analysis**

  - Investigation of amyloid PET imaging for amyloid positivity detection.
  - Processing and analysis of ADNI PET data to identify Alzheimer's-related pathological patterns.
  - Exploration of PET-derived biomarkers associated with disease progression.

### 3. Multimodal Data Integration

A unified multimodal dataset was constructed by combining:

- Demographic information.
- Clinical evaluations.
- Neuropsychological test scores.
- Genetic information.
- Vascular risk factors.
- MRI-derived biomarkers.
- PET-derived biomarkers.

The resulting dataset enables comprehensive patient characterization beyond single-modality approaches.

### 4. Machine Learning and Predictive Modeling

Several machine learning and deep learning approaches were investigated for:

- Cognitive status classification.
- Alzheimer's disease risk assessment.
- Mild Cognitive Impairment progression prediction.

Special attention was given to:

- Data preprocessing and feature engineering.
- Longitudinal patient data management.
- Class imbalance handling.
- Robust patient-level evaluation protocols.
- Comparative analysis of different modeling approaches.

## Datasets

### Frantz Fanon University Hospital (Blida)
- Handwritten neurological patient records.
- Clinical observations and medical reports.
- Real-world healthcare data used for OCR and NLP development.

### Alzheimer's Disease Neuroimaging Initiative (ADNI)
- Structural MRI scans.
- Amyloid PET scans.
- Clinical and cognitive assessments.
- Demographic and genetic information.
- Longitudinal follow-up data.

## Technologies Used

### Artificial Intelligence & Machine Learning
- Python
- PyTorch
- TensorFlow / Keras
- Scikit-learn
- XGBoost
- LightGBM

### Computer Vision & Medical Imaging
- OpenCV
- Medical image processing pipelines
- MRI analysis
- PET analysis

### Natural Language Processing
- Transformer-based language models
- OCR systems
- Clinical information extraction

### Data Science
- Pandas
- NumPy
- Matplotlib
- Statistical analysis and visualization


## System Overview
![Overview of the Multimodal Diagnostic and MCI Stability Prediction Pipeline.](system.png)
