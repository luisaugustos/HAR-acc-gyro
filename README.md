# Enhancing Human Activity Recognition with Machine Learning

This repository contains the reproducible workflows and setup instructions for the study:

> **Enhancing Human Activity Recognition with Machine Learning: Insights from Smartphone Accelerometer and Magnetometer Data**  
> Luis Augusto Silva, Paulo Jorge Coelho, Christophe Soares, Ivo Pereira, Ivan Miguel Pires.

## 📄 Abstract

This study explores the use of accelerometer and magnetometer data from smartphones to classify five Activities of Daily Living (ADLs) using lightweight and interpretable machine learning models. Our approach uses raw, non-normalized data to reduce preprocessing costs and achieve state-of-the-art results in classification accuracy, precision, recall, and F1-score using models like Random Forest and Neural Networks.

## 📦 Contents

- Orange Workflow `.ows` files for reproducibility
- Instructions for setting up the Orange Data Mining environment
- Sample results including confusion matrices and cross-validation scores

## 📊 Dataset

The dataset used in this study includes raw accelerometer, gyroscope, and magnetometer readings collected from a smartphone during the performance of five daily activities. It is publicly available on **Mendeley Data**:

🔗 **[Access the Dataset on Mendeley Data](https://data.mendeley.com/datasets/4x4fwn7dhs/1)**  
**Citation**:  
Pires, Ivan Miguel; Garcia, Nuno (2020), “Dataset for smartphone-based activity recognition using accelerometer and magnetometer”, Mendeley Data, V1. https://doi.org/10.17632/4x4fwn7dhs.1

## 🛠️ Environment Setup

Install Python 3.8+ and the required packages:

```bash
pip install orange3 pandas numpy scipy
```

## ▶️ Running the Workflow

1. Open [Orange3](https://orangedatamining.com/).
2. Import the `.ows` workflow file from this repository.
3. Load the dataset using the **"Import Data"** widget.
4. Execute the workflow to preprocess data, train models, and evaluate results.

## ✅ Performance

| Model           | Accuracy | F1-Score | AUC    |
|----------------|----------|----------|--------|
| Random Forest  | 90.40%   | 90.41%   | 98.30% |
| Neural Network | 90.14%   | 90.13%   | 98.42% |

## 📌 Key Contributions

- Use of raw (non-normalized) data for improved efficiency
- Sensor fusion of accelerometer and magnetometer
- Lightweight, interpretable models suitable for real-time mobile deployment
- Reproducible workflows using Orange3 visual programming

## 📜 License

This project is licensed under the MIT License.

## ✉️ Contact

For questions or collaborations, please contact:  
**Luis Augusto Silva** – [luisaugustos@usal.es](mailto:luisaugustos@usal.es)  
**Ivan Miguel Pires** – [impires@ua.pt](mailto:impires@ua.pt)
