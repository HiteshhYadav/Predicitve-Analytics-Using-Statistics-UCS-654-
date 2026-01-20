Sampling Techniques on Imbalanced Credit Card Dataset
📌 Overview

Imbalanced datasets are a major challenge in real-world machine learning problems such as credit card fraud detection. When one class heavily dominates the dataset, machine learning models tend to become biased toward the majority class.

This project analyzes how different sampling techniques affect the performance of multiple machine learning models on a highly imbalanced credit card dataset.

🎯 Objectives

Understand the impact of class imbalance on model performance

Apply multiple sampling techniques to balance the dataset

Train different machine learning models on sampled data

Compare accuracy across sampling–model combinations

Visualize results for better interpretation

📂 Dataset

Dataset Name: Creditcard_data.csv

Target Column: Class

0 → Non-Fraud

1 → Fraud

The dataset contains a very small number of fraudulent transactions compared to legitimate ones, making it suitable for studying sampling strategies.

🧪 Sampling Techniques Used

The following sampling methods were applied:

Random Over Sampling

Random Under Sampling

SMOTE (Synthetic Minority Oversampling Technique)

SMOTE + Tomek Links

No Additional Sampling

Each sampling technique was evaluated independently to observe its influence on model accuracy.

🤖 Machine Learning Models

Five machine learning models were used in this project:

Model ID	Model
M1	Logistic Regression
M2	Decision Tree Classifier
M3	Random Forest Classifier
M4	Naive Bayes
M5	Support Vector Machine
⚙️ Methodology

Load and preprocess the dataset

Analyze the original class distribution

Balance the dataset using Random Over Sampling

Create five different samples from the balanced dataset

Apply each sampling technique to every sample

Train and test each machine learning model

Evaluate performance using accuracy

Store results and generate visualizations

📊 Results & Visualizations

The following outputs are generated:

Accuracy Matrix showing accuracy for each model–sampling combination

Accuracy Heatmap for easy comparison

Best Sampling Technique per Model

Average Accuracy per Sampling Method

Accuracy Trend Line Plot across sampling techniques

These visualizations make it easy to identify which sampling technique performs best for each model.

📁 Generated Files
File	Description
accuracy_matrix.csv	Accuracy of all model–sampling combinations
best_sampling_per_model.csv	Best sampling technique for each model
avg_accuracy_per_sampling.csv	Average accuracy per sampling method
accuracy_heatmap.png	Heatmap of accuracies
best_accuracy_per_model.png	Best accuracy per model
avg_accuracy_per_sampling.png	Sampling comparison
accuracy_lineplot_all_combinations.png	Accuracy trend plot
🧾 Conclusion

Sampling techniques significantly influence model performance

No single sampling method is optimal for all models

Oversampling and hybrid techniques often improve results

Visual analysis helps in selecting appropriate strategies

This project highlights the importance of choosing suitable sampling techniques when working with imbalanced datasets.

🛠️ Technologies Used

Python

Pandas, NumPy

Scikit-learn

Imbalanced-learn

Matplotlib, Seaborn

▶️ How to Run

Clone the repository

Place Creditcard_data.csv in the project directory

Run the script:

python sampling_assignment.py


Check the generated CSV files and plots

If you want, I can:

✨ shorten this for strict word limits

🧠 add a Discussion / Observation section

📦 create requirements.txt

🏫 align it exactly to your college rubric

Just say the word 👍
