# Quora Insincere Questions Classification

This project uses **TensorFlow Hub** and **transfer learning** for text classification on the **Quora Insincere Questions Classification** dataset.

---

## Overview

This project aims to classify questions from the Quora dataset as either **sincere** or **insincere** using a deep learning model. By leveraging pre-trained TensorFlow Hub modules, the model is fine-tuned to predict the sincerity of questions based on their content. The task involves text preprocessing, model training, and performance evaluation.

---

## Features

- **Dataset**: [Quora Insincere Questions Classification](https://www.kaggle.com/c/quora-insincere-questions-classification)
- **Model**: Pre-trained TensorFlow Hub modules
- **Task**: Binary classification (Sincere vs. Insincere questions)
- **Framework**: TensorFlow 2 and `tf.keras`

---

## Results

The following visualizations provide insights into the dataset:

- **Box Plot**:
  ![Box Plot](https://github.com/leovidith/quoraQuestions-Tensorflow/blob/main/images/box%20plot.png)

- **Output Visualization**:
  ![Output](https://github.com/leovidith/quoraQuestions-Tensorflow/blob/main/images/output.png)

- **Heatmap**:
  ![Heatmap](https://github.com/leovidith/quoraQuestions-Tensorflow/blob/main/images/heatmap.png)

---

## Sprint Features

### **Sprint 1: Data Loading and Preprocessing**
- Load the Quora Insincere Questions dataset.
- Clean and preprocess the text data, including tokenization, removing stopwords, and padding sequences.
- **Deliverable**: Preprocessed dataset ready for training.

### **Sprint 2: Model Architecture**
- Implement a neural network model with TensorFlow, using transfer learning from pre-trained modules.
- Fine-tune the model on the dataset for binary classification.
- **Deliverable**: Model architecture ready for training.

### **Sprint 3: Training the Model**
- Train the model using the preprocessed dataset with an early stopping criterion.
- Monitor the training and validation accuracy to avoid overfitting.
- **Deliverable**: Trained model with evaluation metrics.

### **Sprint 4: Model Evaluation and Optimization**
- Evaluate the model performance using metrics such as accuracy, precision, recall, and F1 score.
- Optimize the model by adjusting hyperparameters and retraining.
- **Deliverable**: Optimized model with performance evaluation.

---

## Conclusion

The Quora Insincere Questions Classification project demonstrates the effectiveness of transfer learning using TensorFlow Hub modules for text classification tasks. The model successfully classifies questions into sincere and insincere categories. Future improvements can include exploring other pre-trained models and further hyperparameter tuning for better accuracy.

---

Let me know if you'd like any further modifications!
