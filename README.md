# Credit Score Classification Using Machine Learning Algorithms

This repository contains code and resources for a machine-learning project focused on credit score classification.<br> 
The project aims to build and evaluate different machine-learning models to predict credit scores based on various features.



## Table of Contents
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Models](#models)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
Credit score classification is a complex problem, depending on many parameters and factors. Payment history, debt-to-credit ratio, length of credit history, new credit, and the amount of credit you have all play a role in your credit report and credit score. All this data is readily available as details of transactions are recorded for all users, and the majority of the youth also use credit cards. In this project, we want to classify the credit score as good, bad, and standard by using these factors and achieving reasonable accuracy. Occupation is also an essential factor for determining the capacity of the user, and many lenders use it for the same.<br>
The **Credit Score Classification Using ML** project aims to develop machine learning models to predict credit scores accurately. The project leverages a dataset of historical credit information and uses various machine learning algorithms to build predictive models. The repository provides code, documentation, and resources necessary to reproduce the results and extend the project further.<br>
Also, in this project, we are classifying credit scores without occupation as this leads to discrimination, and occupations should be treated equally and respectfully. This will also help people with undervalued occupations to get loans if they are eligible.

## Installation
To run the code in this repository, follow these steps:
1. Clone the repository to your local machine using the following command:
   ```shell
   git clone https://github.com/karanprasadgupta/Assembler-and-Simulator.git
   ```
   
## Usage
1. Navigate to the project directory:
   ```shell
   cd Credit-Score-Classification-Using-ML
    ```
2. Open the `code.ipynb` in Jupyter Notebook to explore the code and run the machine learning models.
3. Follow the instructions within the notebook to preprocess the data, train the models, and evaluate their performance.
3. Modify the code and experiment with different models, feature engineering techniques, or hyperparameter settings to improve predictions further.

## Data
The project uses a dataset containing credit-related information. The data is not included in this repository but can be accessed from this [Kaggle Repository](https://www.kaggle.com/datasets/parisrohan/credit-score-classification?resource=download&select=train.csv). Please refer to the provided link for instructions on obtaining the dataset.

Once you have obtained the dataset, place it in the data directory of this repository.

## Models
The repository provides implementations of multiple machine-learning models for credit score classification. Some of the models used in the project are:

* Logistic Regression
* Random Forest
* Decision Tree
* Gaussian Naive Bayes
* Gradient Boosting
* MLP
* KNN
* SVM
* Stack Classifier 
  
You can find the code for each model in the `code.ipynb` notebook. Feel free to explore, modify, or add new models as per your requirements.

## Evaluation
The performance of the machine learning models was evaluated using various metrics, including accuracy, precision, recall, and F1 score. The notebook `code.ipynb` contains code to evaluate the models on the test set and visualize the results.

## Contributing
Contributions to this repository are welcome. If you want to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make the necessary changes and commit them.
4. Push your changes to your forked repository.
5. Submit a pull request describing your changes.

## License
This project is licensed under the [GNU License](./LICENSE). Feel free to modify and use the code as per the license terms.

>This project was developed for learning purposes as part of the CSE343-Machine Learning, Monsoon 2022 semester, Project at IIITD under the supervision of [Prof. Jainendra Shukla](https://www.iiitd.ac.in/jainendra).
