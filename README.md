# Perceptron Classification on Iris Dataset

This project demonstrates a **from-scratch implementation of a Perceptron** classifier on the Iris dataset. It is designed to help beginners understand **how a simple neural network works** and explore **linear classification**.

---

## Project Overview

In this project, we:

- Implemented a **Perceptron class** using NumPy  
- Trained the Perceptron on the **Iris dataset**  
- Predicted the class of test samples  
- Generated a **classification report**  
- Visualized the decision using a **scatter plot**  

> Note: The Perceptron is only effective for **linearly separable classes**.

---

## Technologies Used

- Python 3.x  
- NumPy  
- scikit-learn  
- pandas  
- Matplotlib  

---

## Key Concepts Covered

### 1. Perceptron Implementation
- Custom class with `fit`, `predict`, and `_activation` methods  
- Updates weights and bias using **learning rate** and **error**  

### 2. Dataset Handling
- Used `sklearn.datasets.load_iris`  
- Selected the first two features for visualization  
- Converted target into **binary classes** (`Iris-setosa` vs `Iris-other`)  

### 3. Model Training
- Training is done over multiple **epochs**  
- For each input, the weights and bias are updated according to the Perceptron learning rule  

### 4. Evaluation
- Predictions made on the test set  
- Performance evaluated using `classification_report`  
- Metrics: **precision, recall, f1-score, accuracy**  

### 5. Visualization
- Scatter plot of test data  
- Color-coded points based on Perceptron predictions  
- Helps visualize **linear decision boundaries**

---

## Usage

1. **Clone the repository**:

```bash
git clone https://github.com/your-username/perceptron-iris.git
cd perceptron-iris
```
2. **Install dependencies**:
``` bash 
pip install -r requirements.txt
```
3. **Run the script or notebook**:
``` bash
python perceptron_iris.py
# or open perceptron_iris.ipynb in Jupyter Notebook

```
You will see:

- A **classification report** showing the Perceptron’s performance
- A **scatter plot** showing predicted classes

---

## Learning Outcomes

By completing this project, you will be able to:

- Implement a Perceptron classifier from scratch using Python and NumPy
- Understand how weights and bias are updated during training
- Apply a Perceptron to a **linearly separable dataset**
- Evaluate classification performance using precision, recall, and f1-score
- Visualize predictions and understand decision boundaries

---

## Notes

- The Perceptron works best on **linearly separable classes**
- For multiclass or non-linear datasets, more advanced models like **Logistic Regression or Neural Networks** are recommended
- This project is ideal for beginners learning the **basics of machine learning**

---

## License

This project is open for **educational purposes** and learning.

---

✨ Happy Learning & Machine Learning-ing! ✨
