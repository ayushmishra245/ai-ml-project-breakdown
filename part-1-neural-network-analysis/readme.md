# Customer Churn Prediction using Feed-Forward Neural Networks

## Project Overview

This project focuses on building and analyzing a feed-forward neural network for customer churn prediction. The objective was not only to train a neural network model, but also to understand neural network learning behavior including forward propagation, backpropagation, activation functions, optimization, and hyperparameter tuning.

---

## Dataset Information

The dataset contains customer-related information such as:

- Region
- Plan type
- Contract type
- Payment method
- Monthly charges
- Login activity
- Support tickets
- Satisfaction score
- Data usage
- Payment delays

Target Variable:
- `churn` (Binary Classification)

---

## Tasks Performed

### 1. Dataset Understanding and Exploration
- Dataset shape analysis
- Missing value check
- Statistical summary
- Target variable distribution
- Correlation analysis

### 2. Data Preprocessing
- Dropped irrelevant columns
- One-hot encoding for categorical variables
- Feature scaling using StandardScaler
- Train-test split

### 3. Neural Network Model Building
- Feed-forward neural network using TensorFlow/Keras
- Dense hidden layers
- ReLU activation
- Dropout regularization
- Sigmoid output layer

### 4. Model Training and Evaluation
- Accuracy and loss analysis
- Classification report
- Confusion matrix
- Training and validation performance visualization

### 5. Hyperparameter Experiments
Experiments were performed using:
- Different activation functions
- Different learning rates
- Dropout removal

---

## Model Performance

- Test Accuracy: ~98.5%
- Stable training and validation convergence observed
- Strong overall classification performance

---

## Key Learnings

- Importance of activation functions in neural networks
- Role of weights and biases
- Impact of learning rate on optimization
- Overfitting and regularization concepts
- Challenges of imbalanced datasets

---

## Technologies Used

- Python
- TensorFlow / Keras
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Repository Structure

```text
part-1-neural-network-analysis/
│
├── README.md
├── notebook.ipynb
├── requirements.txt
│
├── results/
│   ├── confusion_matrix.png
│   ├── accuracy_curve.png
│   ├── loss_curve.png
│   └── model_comparison_table.csv