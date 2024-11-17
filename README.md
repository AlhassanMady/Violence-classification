# Enhancing Knowledge Extraction from Violent Ancient Historical Texts through Fine-Tuned Large Language Models and Historical Databases

This repository contains the code, datasets, and scripts associated with my master's thesis: **"Enhancing Knowledge Extraction from Violent Ancient Historical Texts through Fine-Tuned Large Language Models and Historical Databases"**. The research focuses on utilizing fine-tuned large language models (LLMs) like BERT and RoBERTa to automate the classification of violent and non-violent passages in historical texts.

## 📝 Thesis Overview

The thesis explores two main experiments:

1. **Binary Classification**: We used fine-tuned versions of BERT and RoBERTa to classify texts as either violent or non-violent. The models were trained on a custom dataset combining entries from the ERIS database and full texts retrieved from the Perseus Digital Library.

2. **Multi-Class Classification**: We expanded the analysis to categorize violent events across four dimensions:
   - **Level of Violence**: interpersonal, intrapersonal, intersocial, intrasocial
   - **Context**: political, military, social, etc.
   - **Motive**: strategic, emotional, religious, etc.
   - **Long-Term Consequences**: death, conquest, plunder, etc.


## 📂 Project Structure

```plaintext
data/               # Preprocessed datasets used in both experiments
notebooks/          # Jupyter notebooks for data exploration, training, and evaluation
models/             # Pre-trained and fine-tuned models used for classification tasks
src/                # Core scripts for training, fine-tuning, and evaluation
results/            # Evaluation metrics, confusion matrices, and performance reports
```
## 📊 Datasets
The dataset used for this research is based on the ERIS system for violent texts and additional non-violent examples extracted from the Perseus Digital Library. The dataset was further cleaned and preprocessed to ensure a balanced classification dataset.

## 🚀 Getting Started

### Clone the repository:
```bash
git clone https://github.com/AlhassanMady/Violence-classification.git 
cd VIolence-classification
```
## Install dependencies:
```bash
pip install -r requirements.txt
```
## Run the experiments: 
You can use the provided notebooks.


## 📧 Contact
For any questions or collaborations, please reach out via email: [alhassan.abdelhalim@uni-hamburg.de] or [alhassanmady01@gmail.com]
