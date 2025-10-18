# 🧠 Linear Regression from Scratch — Python & NumPy

This project demonstrates a complete implementation of **Linear Regression** from scratch using only **Python and NumPy**.  
It covers fundamental concepts of **Machine Learning**, including cost function computation, gradient derivation, and gradient descent optimization.

---

## 📘 Project Overview
Linear Regression is one of the simplest yet most powerful algorithms in Machine Learning.  
In this project, we:
- Implement the **Cost Function**:  
  J(w,b) = (1 / 2m) * Σ (f_wb(xᶦ) - yᶦ)²
- Compute **Gradients** for parameters w and b:
  ∂J/∂w = (1/m) * Σ (f_wb(xᶦ) - yᶦ)xᶦ  
  ∂J/∂b = (1/m) * Σ (f_wb(xᶦ) - yᶦ)
- Use **Gradient Descent** to update parameters iteratively:
  w := w - α ∂J/∂w  
  b := b - α ∂J/∂b

---

## 🧩 Features
- Compute cost and gradients manually  
- Implement gradient descent loop  
- Visualize training data and fitted line  
- Compare predicted vs actual values  
- Modular code structure with comments  

---

## 🧮 Example Results
| Parameter | Value |
|------------|--------|
| Initial w | 0 |
| Initial b | 0 |
| Final w | ~2.0 |
| Final b | ~0.0 |
| Final Cost | ≈ 0.0 |

---

## 🚀 Technologies Used
- **Python 3**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**

---

## 🧠 Learning Outcomes
- Understand linear regression fundamentals  
- Derive and compute the gradient from scratch  
- Implement optimization using gradient descent  
- Strengthen Python and NumPy vectorization skills  

---

## 📂 Repository Structure
```
linear-regression-from-scratch/
│
├── Linear_Regression_From_Scratch.ipynb   # Main Jupyter Notebook
├── public_tests.py                        # Public test functions (if used)
├── README.md                              # Project documentation
└── data/                                  # (Optional) sample data files
```

---

## 🧑‍💻 Author
**Edwin Kofi Afful**  
📍 Computer Science & Engineering Student  
💡 Passionate about AI, Quantum Computing, and Machine Learning  

---

## 🌟 Acknowledgments
Inspired by Andrew Ng’s *Machine Learning Specialization* and DeepLearning.AI resources.  
Built as part of foundational practice for understanding gradient-based optimization.
