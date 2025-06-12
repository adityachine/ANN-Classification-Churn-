## Deep Neural Networks for Regression Problems

## 📚 Table of Contents
1. [📘 Introduction](#-introduction)  
2. [📊 Project Overview](#-project-overview)  
3. [📁 Files & Folders](#-files--folders)  
4. [🚀 Getting Started](#-getting-started)  
5. [📦 Requirements](#-requirements)  
6. [🛠️ Usage](#-usage)  
7. [📜 License](#-license)

---

## 📘 Introduction

This project demonstrates the use of **Deep Neural Networks (DNNs)** to solve a **regression task**—predicting `EstimatedSalary` from a customer dataset. By leveraging **Keras** and **TensorFlow**, it showcases how deep learning can be effectively applied to structured tabular data.

---

## 📊 Project Overview

The project follows a complete machine learning pipeline:

- 🧹 Data Cleaning & Preprocessing  
- 🧠 Model Building using Deep Neural Networks  
- 🔁 Hyperparameter Tuning  
- 📈 Evaluation & Prediction  
- 💾 Model Serialization for Deployment

The dataset used is `Churn_Modelling.csv`, containing detailed customer information, including age, balance, credit score, and more, used to predict their estimated salary.

---

## 📁 Files & Folders

Here's a breakdown of the project structure:

| File / Folder                | Description                                                 |
|-----------------------------|-------------------------------------------------------------|
| `Churn_Modelling.csv`       | Raw dataset used for model training and evaluation          |
| `app.py`                    | Main Python application for running model and predictions   |
| `experiments.ipynb`         | Experimental notebook for DNN trials and analysis           |
| `hyperparametertuningann.ipynb` | Notebook focused on ANN hyperparameter optimization     |
| `label_encoder_gender.pkl`  | Serialized label encoder for the "Gender" feature           |
| `onehot_encoder_geo.pkl`    | One-hot encoder for the "Geography" feature                 |
| `model.h5`                  | Trained Keras deep learning model (HDF5 format)             |
| `prediction.ipynb`          | Notebook for making predictions using the saved model       |
| `salaryregression.ipynb`    | Core notebook showcasing salary prediction process          |
| `scaler.pkl`                | Pickled scaler for numerical feature normalization          |
| `requirements.txt`          | Project dependency list                                     |
| `runtime.txt`               | Runtime environment specification                           |
| `README.md`                 | This documentation                                          |
| `LICENSE`                   | Project license (MIT)                                       |

---

## 🚀 Getting Started

To run this project locally:

```bash
# Clone the repository
git clone https://github.com/your-username/dnn-regression-project.git
cd dnn-regression-project

# Create virtual environment
python -m venv venv

# Activate it
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
````

---

## 📦 Requirements Deep Neural Networks for Regression Problems


Make sure the following packages are installed (auto-installed via `requirements.txt`):

* Python 3.x
* `pandas`
* `scikit-learn`
* `tensorflow`
* `keras`
* `pickle`
* `jupyter`

---

## 🛠️ Usage

You can run the project in different modes:

### 🔍 Preprocessing & Training

```bash
python app.py
```

or use the Jupyter Notebook:

```bash
jupyter notebook salaryregression.ipynb
```

### 🧪 Model Prediction

Open `prediction.ipynb` and:

1. Load the trained `model.h5`
2. Apply encoders: `label_encoder_gender.pkl`, `onehot_encoder_geo.pkl`
3. Normalize inputs using `scaler.pkl`
4. Predict the salary output

---

## 📜 License

MIT License © 2025
See the [`LICENSE`](./LICENSE) file for full terms and conditions.

---

## 🙌 Acknowledgments

* TensorFlow & Keras for model building
* Scikit-learn for preprocessing
* The open dataset used in `Churn_Modelling.csv`

---

💡 *This project bridges classic tabular regression problems with modern deep learning workflows – a great stepping stone for applied AI in finance, HR, or marketing analytics!*

```
