# Parkinson-Progression-Subtyping

This is implementation of our manuscript "Identification of Parkinson PACE subtypes and repurposing treatments through integrative analyses of multimodal clinical progression, neuroimaging, genetic, and transcriptomic data"


## 1_data_preprocessing
Code for PPMI data extraction and cleaning.

## 2_DPPE
Code for training the DPPE model. 
Input: individuals' high-dimensional, longitudinal clinical records
Output: an embedding vector for each individual

## 3_cluster_analysis
Cluster analysis based on embedding vectors of the PD individuals

## 4_PDBP_validation
Code for validation in the PDBP cohort: including data cleaning, DPPE re-training in PDBP, and clustering

## 
