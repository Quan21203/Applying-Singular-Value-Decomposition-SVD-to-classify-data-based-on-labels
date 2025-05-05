# Applying-Singular-Value-Decomposition-SVD-to-classify-data-based-on-labels

**Vietnamese Text Classification using SVD and SVM**

This Python project implements a **Vietnamese text classification system** that:
✅ Reads and preprocesses text files (tokenization, stopword removal, cleaning)
✅ Uses a machine learning pipeline combining **TF-IDF vectorization**, **Truncated SVD (dimensionality reduction)**, and **SVM classifier**
✅ Trains on labeled data and predicts labels for test data
✅ Automatically organizes test files into folders based on their predicted labels

Key components:

* Vietnamese text preprocessing with `pyvi`
* Stopword removal and special character cleaning
* Feature extraction with `TfidfVectorizer`
* Dimensionality reduction using `TruncatedSVD`
* Classification using `SVC` (Support Vector Machine)
* Automatic file sorting and copying based on predictions

This project is useful for tasks like document classification, organizing unstructured Vietnamese text, and exploring SVD for text data.


