# Handwritten Digit Recognition with Neural Network (NumPy Only)

This project implements a basic neural network from scratch (without TensorFlow or PyTorch) to recognize handwritten digits using the MNIST-like dataset from Kaggle.

---
## 🚀 Overview

- **Model**: 3-layer fully connected neural network
- **Framework**: Built completely using `NumPy`
- **Dataset**: `train.csv` from the [Digit Recognizer](https://www.kaggle.com/competitions/digit-recognizer) competition
- **Accuracy**: Achieves ~90.8% on the dev set

---
## 📂 Structure

- **Input Layer**: 784 neurons (28x28 grayscale pixel values)
- **Hidden Layer**: 64 neurons with ReLU activation
- **Output Layer**: 10 neurons with softmax activation (one for each digit 0–9)


---

## 📊 Key Concepts

- Feedforward Neural Networks
- ReLU and Softmax Activations
- One-Hot Encoding
- Backpropagation Algorithm
- Manual Gradient Descent
- Model Evaluation and Visualization

---

## 📷 Sample Prediction
![Screenshot 2025-06-03 005829](https://github.com/user-attachments/assets/6ed99aeb-eff4-486d-a190-ae9d152b771a)
![Screenshot 2025-06-03 005822](https://github.com/user-attachments/assets/ef7d8011-a135-4cb6-921d-3a01e62969a4)
![Screenshot 2025-06-03 005814](https://github.com/user-attachments/assets/57f42fd0-cdcd-4337-a6ce-06af42fba7a4)

---
## 🧠 Accuracy

- Model achieves **~90.8%** accuracy on dev dataset.
---
## ✅ Requirements

- Python 3.x  
- NumPy  
- Pandas  
- Matplotlib  
---
## 💡 Future Improvements

-Clean or normalize the data for more stable training.
- Rebuild the model using TensorFlow or Scikit-learn for better performance and scalability.
---
## 🔗 Project on Kaggle

You can view the complete project, including code, visualizations, and explanations, on Kaggle:
👉 [View on Kaggle](https://www.kaggle.com/mrx321a/mnist-two-layer-adi)
