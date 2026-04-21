# Diabetic Retinopathy Detection with Deep Learning

This repository contains a collection of experiments and Kaggle notebooks dedicated to the classification of Diabetic Retinopathy (DR) using state-of-the-art deep learning models. The goal is to compare the performance of various architectures on two different, widely-used public datasets.

## 🎯 Objective

The primary objective of this project is to build and evaluate robust classifiers for grading the severity of Diabetic Retinopathy from retinal fundus images. We explore and compare several modern vision models, including Vision Transformers (ViT) and Convolutional Neural Networks (CNNs).

---

## 📊 Datasets

The experiments are conducted on two standard DR detection datasets:

* **APTOS-2019:** The [APTOS 2019 Blindness Detection](https://www.kaggle.com/c/aptos2019-blindness-detection) dataset. It contains thousands of high-resolution retinal images graded into five classes (0: No DR, 1: Mild, 2: Moderate, 3: Severe, 4: Proliferative DR).
* **Messidor:** The [Messidor dataset](https://www.adcis.net/en/third-party/messidor/), which also contains fundus images graded for DR severity.

---

## 🧠 Models Explored

This repository contains notebooks for training and evaluating the following models, both individually and in ensemble combinations:

* **ConvNeXT**
* **MobileViT**
* **ResNet101**
* **Swin Transformer**
* **Ensemble Models** (e.g., `ConvNeXT` + `MobileViT` + `Resnet101`)

---

## 🚀 How to Use

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/prajwal816/Your-Repo-Name.git](https://github.com/prajwal816/Your-Repo-Name.git)
    cd Your-Repo-Name
    ```

2.  **Download Datasets:**
    You must download the [APTOS-2019](https://www.kaggle.com/c/aptos2019-blindness-detection) and [Messidor](https://www.kaggle.com/c/messidor) datasets (e.g., from Kaggle).

3.  **Run Notebooks:**
    You can run these `.ipynb` files in any Jupyter environment (like Jupyter Lab, Google Colab, or directly on Kaggle).

4.  **Install Dependencies:**
    Each notebook should contain the necessary `!pip install` commands at the beginning to install required libraries (such as `timm`, `torch`, `tensorflow`, `scikit-learn`, etc.). Be sure to run these cells first.

5.  **Adjust Paths:**
    Update the data paths within each notebook to point to the location where you have saved the datasets.
