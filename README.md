# FeaRoBERTa: A linguistic Feature Extraction Approach for Fake Review Detection

## Overview
This repository contains the FeaRoBERTa model, a robust machine learning classifier designed to accurately differentiate between real and fake reviews. The model leverages the strengths of the RoBERTa architecture enhanced with unique feature engineering techniques.

## Models
Alongside FeaRoBERTa, this repository also includes evaluation notebooks for other models for comparison:
- RoBERTa_test.ipynb
- BERT-CNN_test.ipynb
- DistilBERT_test.ipynb

## Performance
FeaRoBERTa has demonstrated the following performance metrics:
- Accuracy: 0.78
- Precision: 0.84
- Recall: 0.69
- F1-Score: 0.76
- Loss: 0.44
- Time (s/epoch): 1320

## Setup
To use the FeaRoBERTa model, you need to have a Python environment with necessary libraries installed.

### Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab
- PyTorch
- Transformers library by Hugging Face

### Installing required Python Packages
command: pip install -r requirements.txt


### Usage
Each model is encapsulated in its own Jupyter notebook. To use a model, simply open the corresponding notebook and execute the cells:
- FeaRoBERTa.ipynb for the main model
- RoBERTa_test.ipynb to test the base RoBERTa model
- BERT-CNN_test.ipynb for the BERT-CNN model
- DistilBERT_test.ipynb for the DistilBERT model

### Data
The dataset used to train this model can be found at https://drive.google.com/drive/folders/1tsjFo44Mrqy5WIg_RJvdomdashWahBSH?usp=sharing 