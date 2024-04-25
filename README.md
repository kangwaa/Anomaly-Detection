# Anomaly-Detection
This project aims to enhance my knowledge of machine learning concepts introduced in Computing for Data Analysis Class (CSE6040 - Spring 2024) and apply them to a network intrusion data set. With the proliferation of computer networks and applications, cybersecurity researchers faces challenges in detecting and mitigating intrusions that compromise systems. I will be exploring the UNSW-NB15 dataset (ReadMe available in the folder & Description Below) to explore anomaly detection techniques in Network Security.The data set has 9 attack types along with normal vectors which I aim to be able to model through supervised learning techniques. The main algorithms used in this notebook are Principal Component Analysis for Dimensionality Reduction ,Multiclass Support Vector Machines(SVM) , Gradient Boosting Machines (GBM) and Logistic regression.

Project Steps
1. Exploratory Data:
   - Describe the UNSW-NB15 dataset, including its source, size, and features.
   - Analyze the distribution of data to gain insights into its characteristics.
   - Identify any trends, patterns, or anomalies present in the dataset.
2. Preprocessing Tasks:
   - Handling missing or inconsistent data.
   - Removing outliers to improve model performance.
   - One-hot encoding categorical variables to convert them into numerical format.
   - Scaling features to address variations in their ranges.
   - Addressing dimensionality through Principal Component Analysis (PCA) to reduce the number of features while preserving important information.
3. Anomaly Detection Modeling :
   - Introduce supervised anomaly detection techniques and its relevance in network security.
   - Present the 3 anomaly detection models used and how each does at identfying the different types of attacks:
      -  Multi Class Support Vector Machines
      -  Gradient Boosting Machines (GBM)
      - Logistic Regression
4. Model Fitting ,Evaluation and Testing:
   - Explain the process of fitting each model using preprocessed data.
   - Define evaluation metrics relevant to each model to assess each models performance.
   - Compare and analyze the performance of each model based on evaluation metrics.
   - Provide insights into the effectiveness of different models for detecting network intrusions.
   - Pick the best performing model and test it on test data set.
5. Conclusion and Future Work:
   - Summarize key findings from the analysis and model evaluations and testing.
   - Discuss limitations and potential areas for future improvement.
