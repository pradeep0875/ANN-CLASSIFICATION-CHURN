# ANN-CLASSIFICATION-CHURN

## Overview
This repository contains an Artificial Neural Network (ANN) based classification project focused on predicting customer churn. The primary language used in this project is Jupyter Notebook.

## Introduction
Customer churn prediction is a critical task for businesses to retain valuable customers. This project applies an ANN model to predict whether a customer will churn based on various features such as credit score, geography, gender, age, balance, and more. The dataset used for this project is `Churn_Modelling.csv`, which contains information about 10,000 customers.

## Installation
To get started with this project, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/pradeep0875/ANN-CLASSIFICATION-CHURN.git
cd ANN-CLASSIFICATION-CHURN
pip install -r requirements.txt
```

## Usage
You can run the Jupyter Notebook to explore the data and train the model:

```bash
jupyter notebook
```

Open the `experiments.ipynb` file to see the implementation and results.

Additionally, you can run the Streamlit app to interact with the model:

```bash
streamlit run app.py
```

## Results
The ANN model was trained and evaluated on the dataset. Below are some key results:

- **Accuracy:** The model achieved an accuracy of approximately 85% on the test set.
- **Precision and Recall:** The precision and recall metrics were balanced, indicating the model's effectiveness in identifying both churned and non-churned customers.
- **Churn Probability:** The Streamlit app provides an interactive interface where users can input customer details and get the predicted probability of churn.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## License
This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.
