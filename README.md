# Amharic Intention Detection Using AfroXLM-R

This repository contains the source code, dataset, and experimental framework for **Amharic Intention Detection** using transformer-based deep learning models. The project focuses on automatically identifying the communicative intention expressed in Amharic text, enabling machines to understand the speaker's intended meaning beyond the literal content.

The repository includes data preprocessing scripts, model training and evaluation pipelines, and utilities for reproducing the experimental results. The primary implementation is based on **AfroXLM-R**, a multilingual language model designed for African languages, and is evaluated on a manually annotated Amharic intention dataset.

## Features

* Amharic text preprocessing and normalization
* Tokenization using Hugging Face Transformers
* Fine-tuning of AfroXLM-R for intention classification
* Support for training, validation, and testing
* Performance evaluation using Accuracy, Precision, Recall, and F1-score
* Confusion matrix generation and visualization
* Reproducible experiments with configurable hyperparameters

## Intention Categories

The dataset contains nine intention classes:

* Assertion
* Complaint
* Phatic
* Promise
* Question
* Refusal
* Request
* Sarcasm
* Suggestion

## Repository Structure

```text
├── notebooks/               # Google Colab/Jupyter notebooks 
├── dataset/                 # Amharic intention
         ├── amharic_speech_acts_train.csv 
         ├── amharic_speech_acts_test.csv 
         ├── amharic_speech_acts_val.csv 
├──  # Source code
│   ├── Amharic Intention Detection.ipynb
    ├── Amharic Intention Detection.py

└── README.md
```

## Requirements

* Python 3.10+
* PyTorch
* Transformers
* Datasets
* Scikit-learn
* Pandas
* NumPy
* Matplotlib




## Citation

If you use this repository in your research, please cite the corresponding publication.

## License

This project is released under the MIT License unless otherwise specified.

