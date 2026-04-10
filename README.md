# 🧠 Weight Initialization in Deep Learning (Xavier vs He)

## 📌 Overview

This project demonstrates the importance of **weight initialization** in deep neural networks and how improper initialization leads to **vanishing and exploding gradient problems**.

We implemented and compared:

* ✅ Xavier Initialization (Glorot)
* ✅ He Initialization (Kaiming)

---

## 🚀 Objectives

* Understand the impact of weight initialization
* Solve vanishing gradient problem
* Compare performance of Xavier vs He initialization
* Analyze training stability and convergence

---

## 🧩 Problem Statement

Deep neural networks often suffer from:

* ❌ Vanishing Gradient Problem
* ❌ Exploding Gradient Problem

This project explores how proper initialization techniques help stabilize training.

---

## 🛠️ Technologies Used

* Python 🐍
* NumPy
* TensorFlow / Keras
* Matplotlib

---

## 📊 Weight Initialization Techniques

### 🔹 Xavier Initialization (Glorot)

* Best suited for **Sigmoid / Tanh**
* Maintains balanced variance across layers

**Formula:**
[
Var(W) = \frac{1}{n_{in} + n_{out}}
]

---

### 🔹 He Initialization (Kaiming)

* Best suited for **ReLU activation**
* Handles zeroing effect of ReLU

**Formula:**
[
Var(W) = \frac{2}{n_{in}}
]

---

## ⚠️ Vanishing Gradient Problem

Occurs when gradients become very small during backpropagation.

### 🔍 Effects:

* Slow learning
* Poor accuracy
* Early layers stop updating

---

## 📈 Solution Approach

* Used **Xavier Initialization** for stable gradient flow
* Used **He Initialization** for ReLU-based networks
* Compared loss and accuracy

---

## 📊 Results

| Initialization | Activation | Performance |
| -------------- | ---------- | ----------- |
| Xavier         | Sigmoid    | Stable      |
| He             | ReLU       | Best        |

---

## 🧪 Implementation Steps

1. Load dataset
2. Normalize data
3. Build ANN model
4. Apply different initializers
5. Train model
6. Evaluate performance

---

## 💡 Key Insights

* Initialization plays a crucial role in deep learning
* He initialization performs better with ReLU
* Xavier prevents gradient shrinking in sigmoid networks

---

## 📌 Conclusion

Proper weight initialization ensures:

* Faster convergence
* Stable training
* Better model performance

---

## 📬 Contact

- 📧 Email: mitthapriyanka16@gmail.com
- 🔗 LinkedIn: https://www.linkedin.com/in/priyanka-mittha
- 💻 GitHub: https://github.com/PriyankaMittha
