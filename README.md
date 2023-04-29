# DSCI644-Team-05

Academic Project for the course DSCI644-Software Engineering for Data Science

## Folder Structure

- Notebook (All Jupyter Notebooks)
  - BM25 (Jupyter Notebooks Used For Implementaion of BM25)
  - DataPreprocessing (Jupyter Notebooks Used For Data Preprocessing)
  - DescriptiveAnalysis (Jupyter Notebook Used For Descriptive Analysis)
  - DomainSpecificSiameseCNN (Jupyter Notebooks Used For Implementaion of Siamese CNN with Domain Specific Embedding)
  - LDA_GloVe (Google Colab Notebooks Used For Implementaion of LDA+GloVe)
    - Eclipse: https://colab.research.google.com/drive/19YhpaMoznWbLbbrofdEhvBImK1iWd6Eu
    - Firefox: https://colab.research.google.com/drive/1Qff67xzHm_kGXDfBxFhC6DND_dCw2q47
    - Mobile: https://colab.research.google.com/drive/1fAiyrl-67GbMKs3PaR7t0Gu0UDdt-9nh
  - SiameseCNN (Jupyter Notebooks Used For Implementaion of Siamese CNN)
  - StatisticalAnalysis (Jupyter Notebook Used For Statistical Analysis)
  - TSNEVisualization (Jupyter Notebook Used For t-SNE Visualization)
- PreProcessedData (CSV Files containing Processed Dataset)
  - Eclipse (Processed Eclipse Dataset)
  - Firefox (Processed Firefox Dataset)
  - Mobile (Processed Mobile Dataset)
  - Requirement (To store files used in Notebooks)
- PrimaryDataset (CSV Files containing the Whole Dataset)

## Steps To Run Code

- Step 1: Use Jupyter Notebooks from 'DataPreprocessing' Folder to Pre-Process Data in 'PrimaryDataset' Folder. This Pre-Proessed Data will be stored in 'PreProcessedData' Folder in 'Eclipse', 'Firefox' and 'Mobile' sub-folders accordingly.
- Step 2: Use Jupyter Notebooks from 'BM25' Folder to perform Information Retrieval using BM25.
- Step 3: Use Google Colab Notebooks from 'LDA_GloVe' Folder to perform Topic Modelling using LDA+Glove. Google Colab Notebook Links are provided in Folder Structure. Also make sure required datasets are present in Your Shared Drives so that Code Runs without any issues.
- Step 4: Use Jupyter Notebook from 'StatisticalAnalysis' Folder to perform Statistical Analysis on results of BM25 and LDA+Glove.
- Step 5: Use Jupyter Notebook from 'DescriptiveAnalysis' Folder to perform Descriptive Analysis on Similarity Scores of Bug Reports.
- Step 6: Use Jupyter Notebook from 'TSNEVisualization' Folder to perform Embedding Analysis on Textually Similar and Dissimilar Bug Reports.
- Step 7: Use Jupyter Notebooks from 'SiameseCNN' Folder to perform Machine Learning using SiameseCNN.
  
