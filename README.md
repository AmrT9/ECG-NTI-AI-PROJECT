# ❤️ Heart ECG Detector

A Deep Learning project that uses a **Convolutional Neural Network (CNN)** to classify ECG signals into multiple abnormal cardiac classes.

## 📌 Project Overview

This project applies deep learning techniques to **Electrocardiogram (ECG) signal classification**, aiming to identify different types of cardiac abnormalities from ECG time-series data.

The project includes data preprocessing, feature preparation, CNN model development, training, and performance evaluation across four abnormal ECG classes.

## 🧠 Methodology

The overall workflow consists of:

**ECG Dataset → Data Preprocessing → Feature Preparation → CNN Model → Training → Classification → Evaluation**

### Data Processing

* Prepared and processed ECG time-series data.
* Applied preprocessing techniques to make the signals suitable for deep learning.
* Prepared the input features for CNN-based classification.

### Deep Learning Model

* Developed a **Convolutional Neural Network (CNN)** for multi-class ECG classification.
* Trained the model to distinguish between different abnormal ECG classes.
* Evaluated the model using multiple classification metrics.

## 📊 Results

| Metric            |    Result |
| ----------------- | --------: |
| Overall Accuracy  | **96.5%** |
| Weighted F1-Score | **96.6%** |

The model demonstrated strong classification performance across most classes.

For example:

* **Class 3 Precision:** 99.3%
* **Class 3 Recall:** 99.2%

The project also identified challenges associated with **minority classes**, particularly Class 2, highlighting the impact of class imbalance on model performance.

## 🛠️ Technologies

* Python
* TensorFlow / Keras
* Convolutional Neural Networks (CNN)
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Google Colab

## 🏥 Application

The project demonstrates a practical application of **Artificial Intelligence in healthcare**, showing how deep learning models can be applied to ECG signals to support the identification of cardiac abnormalities.

> **Note:** This project is an academic/experimental machine learning system and is not intended for clinical diagnosis or medical decision-making.

## 📓 Notebook

The complete implementation is available in the Jupyter Notebook:

`ECG_Analysis.ipynb`

The notebook contains the preprocessing, model development, training, evaluation, and results.

## 🚀 How to Run

1. Clone or download this repository.
2. Open `ECG_Analysis.ipynb`.
3. Install the required Python dependencies.
4. Run the notebook cells sequentially.

The project can also be run using **Google Colab**.

## 👨‍💻 Author

**Amr Tarek Abdelmoez Ismail**

Computer Science Undergraduate
Nile University of Egypt

