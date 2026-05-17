# Part 1 - Neural Network Analysis

## What this is about

This part of the project is about building a neural network to predict customer churn. The dataset has information about telecom customers like how long they have been with the company, how much they pay, how many support tickets they raised etc. The goal is to predict whether a customer will churn (leave) or not.

## Dataset

File: `customer_churn_nn.csv`

It has 2000 rows and 17 columns. The target column is `churn` where 1 means the customer left and 0 means they stayed. Most customers did not churn so the data is a bit imbalanced.

## What I did

- Loaded the dataset and did basic exploration
- Cleaned and preprocessed the data (handled categorical columns, scaled numerical ones)
- Built a neural network using Keras
- Trained the model and checked accuracy
- Ran 3 different experiments by changing layers, neurons, learning rate etc
- Wrote a reflection on what I learned

## How to run

1. Install the requirements first:

```
pip install -r requirements.txt
```

2. Open the notebook:

```
jupyter notebook notebook.ipynb
```

Make sure the dataset file `customer_churn_nn.csv` is in the same folder as the notebook.

## Results

The results are saved in the `results/` folder:

- `model_comparison_table.csv` - shows how each experiment performed
- `evaluation_outputs.png` - training curves, confusion matrix and accuracy comparison

## Files in this folder

```
part-1-neural-network-analysis/
├── README.md
├── notebook.ipynb
├── requirements.txt
├── customer_churn_nn.csv
└── results/
    ├── model_comparison_table.csv
    └── evaluation_outputs.png
```


