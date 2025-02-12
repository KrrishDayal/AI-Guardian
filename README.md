# Anomaly Detection in Large-Scale Data Using Autoencoders

## Project Description
This project implements an **Anomaly Detection System** using **Deep Learning (Autoencoders)**. The goal is to identify **abnormal patterns in large-scale datasets** that may indicate fraud, cyber intrusions, or irregular system behaviors. The model was trained and evaluated using **ROC AUC Score, Precision, Recall, and F1-score** to ensure high accuracy.

## Dataset
- **Dataset Used:** Large-scale anomaly dataset (e.g., network traffic, financial transactions, etc.).
- **Preprocessed Data Shape:** `(494021, 118)`
- **Training Samples:** `77,822`
- **Validation Samples:** `19,456`
- **Test Samples:** `494,021`
- **Anomalies Detected:** Identifies outliers based on learned patterns.

## Achievements
- **ROC AUC Score:** `0.9865`
- **Model Type:** Deep Learning-based Autoencoder.
- **Performance Metrics:**  
  - **Precision:** `99%`  
  - **Recall:** `95%` (for normal class)  
  - **Accuracy:** `99%`  
- **Model Saved As:** `autoencoder_model.h5`

## 📝 License  

This project is licensed under the **MIT License** 

## Acknowledgments  

- **Dataset:** KDD Cup 99 (via scikit-learn)  
- **Libraries Used:** TensorFlow, Scikit-learn, Pandas, Matplotlib  
- **Inspiration:** Research in anomaly detection and cybersecurity  

If you find this project useful, consider **starring** the repository!   

