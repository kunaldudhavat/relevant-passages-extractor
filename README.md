# Relevenat Passages Extractor

## Introduction

This repository contains a project on implementing a Dual Encoder model for retrieving relevant passages given a question. The implementation is done in Python using Jupyter Notebook.

## Table of Contents

- [Introduction](#introduction)
- [Project Description](#project-description)
- [Dataset](#dataset)
- [Approach](#approach)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Description

### Dual Encoder Model

The Dual Encoder model consists of two encoders: one for encoding the questions and another for encoding the passages. The model computes the similarity between the encoded representations to retrieve the most relevant passage for a given question.

### Key Components

1. **DistilBERT Encoder**: Encoding the questions and passages using DistilBERT.
2. **Similarity Calculation**: Computing the similarity between encoded question and passage representations.
3. **Contrastive Loss**: Implementing in-batch contrastive loss for training the model.
4. **Hard Negative Mining**: Including hard negatives during training to improve model performance.

## Dataset

We will use the Natural Questions (NQ) Dataset. The dataset used in this project consists of question and passage pairs. The dataset would be stored under directory data/nq-toy/. 

## Approach

The approach taken in this project includes the following steps:

1. **Data Preprocessing**: Loading and preprocessing the dataset, including tokenization and padding.
2. **Model Implementation**: Implementing the Dual Encoder model components, including DistilBERT encoders and similarity calculation.
3. **Training**: Training the Dual Encoder model using contrastive loss.
4. **Evaluation**: Evaluating the trained model on the test set and comparing the performance of different training strategies.

## Requirements

- Python 3.8+
- Jupyter Notebook
- NumPy
- Matplotlib
- Pandas
- TensorFlow or PyTorch
- Transformers (Hugging Face)

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/dual-encoder.git
   cd dual-encoder

## Usage

1. Running the notebook:
   ```sh
   jupyter notebook
  
2. Open the dual-encoder.ipynb file and run all the cells


## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

