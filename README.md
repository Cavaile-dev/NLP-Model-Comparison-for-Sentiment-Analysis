This project presents a comparative analysis of different NLP models for multi-class sentiment analysis on a dataset of social media text. The objective is to evaluate and compare the performance of modern transformer-based architectures against a traditional machine learning approach.

The notebook begins by cleaning and preparing a labeled dataset, dropping empty rows, and encoding categorical labels into a numerical format.

Model Architectures:

✅Transformer Models: Three popular transformer models—BERT, RoBERTa, and DistilBERT—are fine-tuned for the sentiment classification task.

✅Traditional ML: A traditional approach is implemented using TF-IDF for feature extraction, followed by a Logistic Regression classifier.

✅Evaluation: The performance of each model is rigorously evaluated on a validation set using standard metrics, including Accuracy, F1 Score (weighted), and ROC AUC.

📝Key Findings:

The results of the analysis are summarized in a comparison table, clearly showing the performance of each model on the validation data. The fine-tuned BERT model demonstrates superior performance across all metrics, highlighting the effectiveness of large language models for this specific task.
