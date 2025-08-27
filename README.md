# Anomaly Detection using Machine Learning Models

This repository presents a project on **Anomaly Detection**, focusing on identifying unusual patterns or outliers in datasets using **unsupervised machine learning models**. Anomalies often represent critical events such as fraud, network intrusions, equipment malfunctions, or irregular system behavior, making detection highly valuable across multiple domains.

The project implements three widely used algorithms:

* **Local Outlier Factor (LOF):** Detects anomalies by measuring local deviation of density with respect to neighbors.
* **One-Class SVM:** Learns a decision function for novelty detection, classifying whether new observations resemble the training data.
* **DBSCAN (Density-Based Spatial Clustering):** Groups data into clusters and labels points in sparse regions as anomalies.

### Features

* Input support for **CSV/Excel datasets**.
* Visualization of anomalies using **Matplotlib/Seaborn**.
* Evaluation metrics such as **accuracy, precision, recall, and F1-score**.
* Modular design for extending additional

# Requirement
### Core
python 3.8

### GUI
PyQt5, PyQt6 and tkinter

### Data processing
pandas and numpy

### Machine Learning
scikit-learn, keras and tensorflow

### Visualization
matplotlib and seaborn
