# Machine Learning Foundations (Cornell / Break Through Tech AI)

My coursework from **Machine Learning Foundations**, the summer 2024 course in the [Break Through Tech AI](https://www.breakthroughtech.org/) program, delivered through eCornell with a curriculum from Cornell Tech and Cornell University faculty.

Each notebook follows the machine learning life cycle: define the problem, explore and prepare the data, train and tune models, and evaluate the results.

## Repository structure

```
Labs/          weekly lab notebooks (Labs 1 to 8)
Assignments/   unit coding assignments (Units 2 to 8)
```

## Labs

| Lab | Notebook | Topic | Data |
|---|---|---|---|
| 1 | [Problem Formulation](Labs/Lab1_ML_Life_Cycle_Problem_Formulation.ipynb) | NumPy, pandas, and Matplotlib practice, then framing ML problems | Airbnb NYC listings, housing prices, restaurant rankings, zoo animals, flight delays |
| 3 | [Compare KNNs and Decision Trees](Labs/Lab3_CompareKNNsAndDTs.ipynb) | Training and comparing KNN and decision tree classifiers | Airbnb NYC listings |
| 4 | [Logistic Regression from Scratch](Labs/Lab4_LogisticRegressionFromScratch.ipynb) | Writing a logistic regression class with gradient descent, the gradient, and the Hessian | Airbnb NYC listings |
| 5 | [Model Selection for Logistic Regression](Labs/Lab5_ModelSelectionForLogisticRegression.ipynb) | Hyperparameter tuning and model evaluation | Airbnb NYC listings |
| 6 | [Comparing Regression Models](Labs/Lab6_ComparingRegressionModels.ipynb) | Individual and ensemble regressors | Airbnb NYC listings |
| 7 | [Implementing a CNN](Labs/Lab7_ImplementCNN.ipynb) | Convolutional neural network with Keras for handwritten digits | MNIST |
| 8 | [Define and Solve an ML Problem](Labs/Lab8_DefineAndSolveMLProblem.ipynb) | Final project: predicting national happiness scores | World Happiness Report 2018 |

## Unit assignments

| Unit | Notebook | Topic | Data |
|---|---|---|---|
| 2 | [Prepare a Data Set for Modeling](Assignments/Unit2_BuildModelingDataset.ipynb) | Cleaning, outliers, missing values, and feature engineering | U.S. Census (adult income) |
| 4 | [Optimizing Logistic Regression](Assignments/Unit4_OptimizingLogisticRegression.ipynb) | Tuning regularization strength (C) | Cell2Cell telecom churn |
| 5 | [Model Selection for KNN](Assignments/Unit5_ModelSelectionForKNN.ipynb) | Grid search and cross-validation for KNN | Cell2Cell telecom churn |
| 7 | [Implement a Neural Network](Assignments/Unit7_ImplementNeuralNetwork.ipynb) | Feedforward neural network with Keras for binary classification | Airbnb NYC listings |
| 8 | [Neural Network for Sentiment Analysis](Assignments/Unit8_NeuralNetworkSentimentAnalysis.ipynb) | TF-IDF features and a feedforward network for text classification | Book reviews |

## Highlight: final project (Lab 8)

I predicted each country's happiness score (the Life Ladder) from six national indicators: log GDP per capita, social support, healthy life expectancy, freedom to make life choices, generosity, and perceptions of corruption. After a linear regression baseline (R² 0.727), I tuned decision tree, random forest, and gradient boosting models with grid search. The random forest performed best, with R² 0.853.

Read the full case study on my site: [World Happiness Prediction](https://veradureke.com/projects/world-happiness-prediction/).

## Tools

Python · NumPy · pandas · Matplotlib · Seaborn · scikit-learn · TensorFlow / Keras · Jupyter

## Notes

The notebooks ran in the course's Codio environment, so the data files are not included here. Course materials and starter code belong to Cornell and Break Through Tech AI; my solutions and analysis are my own.
