Multi-Classification Project: Network Intrusion Detection

Project Overview

This project aimed to enhance my knowledge of machine learning concepts introduced in my Master’s program at Georgia Tech and apply them to a network intrusion dataset. With the proliferation of computer networks and applications, cybersecurity researchers face challenges in detecting and mitigating intrusions that compromise systems. I explored the UNSW-NB15 dataset (ReadMe available in the folder & Description Below) to apply classification techniques in Network Security. The dataset has nine attack types along with normal vectors, which I modelled through supervised learning techniques. The main algorithms used in this notebook are Principal Component Analysis for Dimensionality Reduction, Naive Bayes Classifier, Logistic Regression, K-Nearest Neighbors, and Neural Networks.

Project Steps

1.	Exploratory Data Analysis:
	•	Described the UNSW-NB15 dataset, including its source, size, and features.
	•	Analyzed the distribution of data to gain insights into its characteristics.
	•	Identified trends, patterns, or anomalies present in the dataset.
2.	Preprocessing Tasks:
	•	Handled missing or inconsistent data.
	•	Removed outliers to improve model performance.
	•	One-hot encoded categorical variables to convert them into numerical format.
	•	Scaled features to address variations in their ranges.
	•	Addressed dimensionality reduction through PCA to reduce the number of features while preserving important information.
3.	Classification Models:
	•	Introduced classification techniques and their relevance in network security.
	•	Presented and explained the four classification models used:
	•	Naive Bayes
	•	K-Nearest Neighbors
	•	Multi-Class Support Vector Machines
	•	Logistic Regression
4.	Model Fitting, Evaluation, and Testing:
	•	Model Fitting: Each model was trained using the preprocessed data, which involved handling missing values, scaling features, and applying dimensionality reduction techniques.
	•	The models used were Naive Bayes, Logistic Regression, K-Nearest Neighbors (KNN), and Neural Network.
	•	Performance Evaluation: Each model’s performance was compared based on the evaluation metrics.
	•	Evaluation Metrics: The metrics used to assess each model’s performance were Accuracy, Precision, Recall (Sensitivity), and F1 Score.
	•	Model Comparison: The accuracy, precision, recall, and F1 scores for each model were calculated and analyzed.
	•	Insights: Insights were drawn on how effectively each model detects different types of network intrusions. The analysis highlighted the strengths and weaknesses of each model in classifying normal traffic versus various attack types.
	•	Neural Network Classifier: Achieved the highest accuracy and F1 score, indicating strong overall performance and a good balance between precision and recall.
	•	Logistic Regression: Demonstrated robust performance, especially for linearly separable datasets, with high accuracy and a good F1 score.
	•	K-Nearest Neighbors (KNN): Showed effectiveness in handling local patterns with a high F1 score, making it suitable for datasets with significant local structures.
	•	Naive Bayes: Had the lowest accuracy and F1 score, reflecting limitations due to its assumption of feature independence.
	•	Best Performing Model: The best-performing model was selected based on a comprehensive analysis of the evaluation metrics and tested on a separate test dataset to validate its performance. This step ensured that the model generalizes well to unseen data and effectively detects intrusions in a real-world scenario.
5.	Conclusion and Future Work:
	•	Evaluation Metrics Summary: Discussed the evaluation metrics derived from the four models and provided a summary of key findings.
	•	The Neural Network and KNN models were most effective in balancing precision and recall, making them suitable for intrusion detection tasks where both false positives and false negatives are critical considerations.
	•	Logistic Regression also performed well, particularly in datasets with linear separability after PCA transformation.
	•	Naive Bayes, while less effective in this context, remains a valuable model for its simplicity and efficiency in other scenarios.
   

   
