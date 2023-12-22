# Breast Cancer Wisconsin Diagnostic Data Set Analysis

## Overview
This repository contains a machine learning project that uses the Breast Cancer Wisconsin (Diagnostic) Data Set to classify tumors as malignant or benign.

## Dataset
The dataset features measurements from a digitized image of a fine needle aspirate (FNA) of a breast mass, with attributes that describe the characteristics of the cell nuclei present in the image.

## Features
There are 30 numeric features in the dataset, computed from the FNA image, which include:

- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Concave points
- Symmetry
- Fractal dimension

## Methodology
We utilize a Random Forest Classifier for this predictive task. The process involves data preprocessing, model training, and evaluation. The model's performance is assessed using accuracy, precision, recall, and F1-score metrics, as well as a confusion matrix for more detailed analysis.

## Results
The model achieved an impressive accuracy of over 97%, with high precision and recall values, indicating its effectiveness in classifying the tumor cases correctly.

## Installation
To install the required Python libraries, run the following command:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn

```

## Usage

The analysis is carried out in a Jupyter Notebook, allowing for an interactive exploration of the data and results.

To view and run the notebook:

1. Ensure that you have Jupyter installed. If you do not have Jupyter installed, you can install it using Anaconda or with pip:

    Using Anaconda:
    ```
    conda install -c conda-forge notebook
    ```

    Using pip:
    ```
    pip install notebook
    ```

2. Clone this repository to your local machine:

    ```
    git clone https://github.com/your-username/your-repository-name.git
    ```

3. Navigate to the cloned directory and start the Jupyter Notebook server:

    ```
    cd your-repository-name
    jupyter notebook
    ```

4. Open the `breast_cancer_winsconsin.ipynb` and the `trained_model_bc_winsconsin.ipynb` notebook and run the cells to see the analysis and results.

Ensure all necessary Python packages from the `requirements.txt` file are installed before running the notebook.

## Contributing
Contributions are welcome. To contribute, please fork the repository, make your changes, and submit a pull request. Feel free to help me implement my code, I'm a newbie, so any kinds of insights and improvement are welcome.

## License
This project is released under the MIT License.

## Acknowledgments
Thanks to the UCI Machine Learning Repository for providing the dataset used in this project.


 `Kevyn Castelo Branco` `2023` 
