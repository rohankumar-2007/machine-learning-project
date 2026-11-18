# machine-learning-project
# 🌸 Iris Flower Classification using Neural Networks

## 📌 Project Overview

This project uses Machine Learning and Deep Learning to classify Iris flowers into three different species based on their flower measurements.

A neural network is developed using **Keras and TensorFlow**, and the model is evaluated using **10-Fold Cross-Validation** with Scikit-learn.

The main goal is to predict the species of an Iris flower based on its sepal and petal measurements.

## 🎯 Objectives

- Analyze the Iris flower dataset.
- Visualize flower measurements using scatter plots.
- Separate input features and output labels.
- Convert categorical labels using Label Encoding and One-Hot Encoding.
- Build a neural network using Keras.
- Evaluate model performance using 10-Fold Cross-Validation.

## 📊 Dataset Information

The dataset contains measurements of Iris flowers.

### Input Features

| Feature | Description |
|---|---|
| Sepal Length | Length of the sepal in centimeters |
| Sepal Width | Width of the sepal in centimeters |
| Petal Length | Length of the petal in centimeters |
| Petal Width | Width of the petal in centimeters |

### Target Classes

The model classifies flowers into three species:

- Iris Setosa
- Iris Versicolor
- Iris Virginica

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- TensorFlow
- Keras
- Scikit-learn
- Matplotlib

## 🧠 Model Architecture

The project uses a simple Sequential Neural Network.

- **Input Layer:** 4 input features
- **Hidden Layer:** 8 neurons with ReLU activation
- **Output Layer:** 3 neurons with Softmax activation

### Model Configuration

| Parameter | Value |
|---|---|
| Model Type | Sequential Neural Network |
| Hidden Neurons | 8 |
| Activation Function | ReLU |
| Output Activation | Softmax |
| Loss Function | Categorical Crossentropy |
| Optimizer | Adam |
| Epochs | 200 |
| Batch Size | 5 |

## ⚙️ Project Workflow

1. Import the required libraries.
2. Load the Iris dataset.
3. Visualize the flower measurements.
4. Separate the input features and target labels.
5. Encode the target labels.
6. Build the neural network model.
7. Train and evaluate the model.
8. Perform 10-Fold Cross-Validation.
9. Calculate the average model accuracy.

## 📈 Model Evaluation

The model performance is evaluated using **10-Fold Cross-Validation**.

The dataset is divided into 10 parts. The model is trained and tested repeatedly, with different parts used for validation.

The final evaluation reports:

- Mean accuracy
- Standard deviation of accuracy

This helps understand the model's performance across different data splits.

## 📂 Project Structure

```text
Iris-Flower-Classification/
│
├── Iris_flower_classification.ipynb
├── data/
│   └── iris_dataset.csv
│
└── README.md
```

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Iris-Flower-Classification.git
```

### 2. Navigate to the Project Folder

```bash
cd Iris-Flower-Classification
```

### 3. Install Required Libraries

```bash
pip install pandas numpy tensorflow scikit-learn matplotlib
```

### 4. Open Jupyter Notebook

```bash
jupyter notebook
```

Open `Iris_flower_classification.ipynb` and run the notebook cells sequentially.

## 📌 Expected Output

The notebook displays:

- Iris dataset preview
- Flower measurement visualizations
- Neural network model evaluation
- Cross-validation accuracy results

The final output shows the baseline prediction accuracy and its standard deviation.

## 📚 Learning Outcomes

- Understanding classification problems in Machine Learning
- Working with the Iris dataset
- Data visualization using Python
- Label encoding and One-Hot Encoding
- Building neural networks with Keras
- Evaluating models using Cross-Validation

## 👨‍💻 Author

**Your Name**

---

⭐ If you find this project useful, feel free to star the repository!
