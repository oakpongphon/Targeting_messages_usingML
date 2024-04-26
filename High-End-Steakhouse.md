# High-End Steakhouse Deal Analysis

As a new member of Susan Liu's analytics team at Tuango, I was tasked with running and evaluating a new deal for a major high-end steakhouse. Tuango is similar to Groupon, promoting discounted gift certificates for use at local or national retailers. This new project followed the success of the previous Karaoke deal project.

## Project Background
The negotiations with the steakhouse were challenging. The average price per meal at the restaurant was 600 RMB, but Tuango was only able to secure a 25% commission. Susan Liu, the Chief Data Scientist, advised me to consider 12 RMB as the cost for each SMS sent to a customer.

Given this context, my assignment was to estimate a logistic regression model to assess the deal's potential success. The data provided included a training sample and a test sample.

## Additional Analyses and Tasks
The evening before a critical meeting, Susan Liu requested the following additional analyses:

1. **Neural Network Estimation**: A single-layer neural network with one node and regularization of 0.5, using `tanh` and `lbfgs`.
2. **Random Forest Estimation**: A random forest with 100 trees, sampling one feature for each node split.
3. **Model Performance Evaluation**: Assessing profit and Return on Marketing Expenditure (ROME) for all three models (logistic regression, neural network, and random forest) using a gains chart to ensure there was no overfitting.

Due to unforeseen circumstances, I had to conduct these analyses at the last minute to ensure the success of the meeting with the CEO.

## Model Tuning and Further Analysis
Following the meeting, Susan Liu requested additional model tuning:

- **Neural Network Tuning**: Conducting 5-fold cross-validation to evaluate models with one hidden layer, varying the number of nodes (1, 2, 3, and 4) and regularization (0, 0.5, 1). The goal was to determine if the original neural network structure was optimal.
- **Random Forest Tuning**: Similarly, applying 5-fold cross-validation over a grid with 100, 200, and 300 trees, and sampling 1, 2, or 3 features for each node split.

Both cross-validations aimed to evaluate model performance using Area Under the Curve (AUC). I reported the best model specifications for both the neural network and the random forest.

## Results and Outcomes
I compared the models' performance in terms of profit and ROME to determine the best approach for targeting. The results from these analyses informed Tuango's decision-making for their new marketing campaign targeting 250,000 customers.

