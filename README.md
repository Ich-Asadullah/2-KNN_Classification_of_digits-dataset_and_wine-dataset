# KNN Classification of Digits and Wine Datasets

This repository contains the implementation of K-Nearest Neighbors (KNN) classification on two datasets: the Digits dataset and the Wine dataset from scikit-learn. The project demonstrates the entire workflow, including data preprocessing, model training, evaluation, and visualization of results.

## Table of Contents

- [Introduction](#introduction)
- [Datasets](#datasets)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

K-Nearest Neighbors (KNN) is a simple, supervised machine learning algorithm that can be used for both classification and regression tasks. In this project, we use KNN to classify images of handwritten digits and types of wine based on their chemical properties.

![KNN Classification](img/Thumbnail.jpeg)

## Datasets

### Digits Dataset

The Digits dataset contains 1,797 samples of handwritten digits (0-9) with 64 features each, representing 8x8 pixel images.

### Wine Dataset

The Wine dataset consists of 178 samples with 13 features, representing different chemical properties of wines. The task is to classify the wines into three classes.

## Installation

To get started, clone this repository and install the required dependencies.

```bash
git clone https://github.com/yourusername/knn-classification-digits-wine.git
cd knn-classification-digits-wine
pip install -r requirements.txt
```

## Usage
The project contains Jupyter notebooks for each dataset. To run the notebooks, start Jupyter Lab or Jupyter Notebook.

```bash 
jupyter lab
```
Open the KNN_Classification_of_digits-dataset_and_wine-dataset.ipynb notebooks to explore the KNN classification process for each dataset.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes.
Commit your changes (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Open a pull request.

## License
This project is licensed under the MIT License.
