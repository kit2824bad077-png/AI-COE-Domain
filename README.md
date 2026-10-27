
# ANN Binary Classification Using the make_moons Dataset

## 📌 Project Description
This project develops an Artificial Neural Network (ANN) for binary classification using the make_moons dataset from Scikit-learn. The model learns to classify data points into two different classes using deep learning techniques.

## 🎯 Objectives
- Generate a binary classification dataset.
- Preprocess and scale the input features.
- Build an Artificial Neural Network using TensorFlow and Keras.
- Train the model to classify data points.
- Evaluate the model using performance metrics.
- Visualize the dataset and decision boundary.

## 🛠️ Technologies Used
- Python
- NumPy
- Matplotlib
- Scikit-learn
- TensorFlow and Keras
- Google Colab / Jupyter Notebook

## 📊 Dataset Details
- **Dataset:** make_moons
- **Number of samples:** 1000
- **Number of features:** 2
- **Number of classes:** 2
- **Noise:** 0.2
- **Training set:** 80%
- **Testing set:** 20%

## 🧠 ANN Architecture
1. Input layer: 2 features
2. Hidden layer: 16 neurons with ReLU activation
3. Hidden layer: 8 neurons with ReLU activation
4. Output layer: 1 neuron with Sigmoid activation

### Model Configuration
- **Optimizer:** Adam
- **Loss Function:** Binary Cross-Entropy
- **Epochs:** 100
- **Batch Size:** 32

## ⚙️ Implementation Steps
1. Import the required libraries.
2. Generate the make_moons dataset.
3. Visualize the dataset.
4. Split the dataset into training and testing sets.
5. Normalize the features using StandardScaler.
6. Build and compile the ANN model.
7. Train the model using training data.
8. Plot training and validation accuracy and loss.
9. Evaluate the model on test data.
10. Display the classification report and confusion matrix.
11. Visualize the decision boundary.

## 📈 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Training and Validation Loss

## 🚀 How to Run

### Google Colab
1. Open https://colab.research.google.com/
2. Upload the notebook file.
3. Run all cells in order.
4. Observe the training graphs and evaluation results.

### Local Installation
Install the required libraries:

```bash
pip install numpy matplotlib scikit-learn tensorflow
```

Open the notebook in Jupyter Notebook and run all cells.

## ✅ Expected Results
- Dataset visualization
- ANN model summary
- Training and validation accuracy graph
- Training and validation loss graph
- Test accuracy and loss
- Classification report
- Confusion matrix
- Decision boundary visualization

## 📝 Conclusion
This project demonstrates how an Artificial Neural Network learns nonlinear patterns and performs binary classification. It provides practical experience in data preprocessing, model training, evaluation, and visualization using deep learning.

## 👩‍💻 Project Information
**Project Type:** Deep Learning  
**Task:** Binary Classification  
**Model:** Artificial Neural Network (ANN)
