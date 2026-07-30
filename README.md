# Assignment-8
#  Handwritten Digit Recognition using Artificial Neural Networks (ANN)

A Machine Learning project developed as part of **AI-ML Assignment 8**. This project recognizes handwritten digits (0–9) using an Artificial Neural Network (ANN) trained on the MNIST Handwritten Digits Dataset.

---

#  Objective

The objective of this project is to classify handwritten digits (0–9) using an Artificial Neural Network (ANN). The model is trained on the MNIST dataset and evaluated using standard classification metrics.

---

#  Dataset

**Dataset Name**

MNIST Handwritten Digits Dataset

**Dataset Link**

https://www.kaggle.com/datasets/oddrationale/mnist-in-csv

---

#  Libraries Used

- Pandas
- NumPy
- Matplotlib
- TensorFlow / Keras
- Scikit-learn

---

#  Methodology

## Step 1: Data Understanding

- Loaded the dataset using Pandas.
- Displayed the first five records.
- Identified input features and target variable.
- Displayed dataset dimensions and information.
- Visualized one handwritten digit.

---

## Step 2: Data Preprocessing

- Checked for missing values.
- Separated features and target labels.
- Normalized pixel values to the range 0–1.
- Split the dataset into training and testing sets.
- Converted target labels into one-hot encoded vectors.

---

## Step 3: Model Architecture

The Artificial Neural Network consists of:

- **Input Layer:** 784 input neurons
- **Hidden Layer 1:** 128 neurons (ReLU)
- **Hidden Layer 2:** 64 neurons (ReLU)
- **Output Layer:** 10 neurons (Softmax)

---

## Step 4: Model Training

- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Evaluation Metric: Accuracy
- Epochs: 10

---

## Step 5: Model Evaluation

The model was evaluated using:

- Test Accuracy
- Confusion Matrix
- Classification Report
- Accuracy vs Epoch Graph
- Loss vs Epoch Graph

---

#  Results

The ANN model achieved high accuracy in recognizing handwritten digits. The training and validation accuracy improved over the training epochs, while the confusion matrix showed that most digits were correctly classified.

---

#  Conclusion

An Artificial Neural Network (ANN) was successfully developed to recognize handwritten digits using the MNIST dataset. After preprocessing the data, the model was trained with two hidden layers and evaluated using test accuracy, a confusion matrix, and a classification report. The ANN achieved strong performance in digit recognition. Hidden layers enabled the model to learn complex image features effectively. Deep Learning offers superior automatic feature learning compared to traditional machine learning methods, although ANN models require greater computational resources and longer training time.

---

#  Repository Structure

```text
Assignment-8/
│
├── Assignment-8.ipynb
└── README.md
```

---

#  How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Assignment-8.git
```

### 2. Install Required Libraries

```bash
pip install pandas numpy matplotlib tensorflow scikit-learn
```

### 3. Open the Notebook

Open **Assignment-8.ipynb** in Google Colab or Jupyter Notebook.

### 4. Run All Cells

Run all notebook cells from top to bottom.

---

#  Author

**Name:** Sougat Das

**Course:** B.Tech CSE (AI & ML)

**Assignment:** Assignment-8

**Topic:** Handwritten Digit Recognition using Artificial Neural Networks (ANN)
