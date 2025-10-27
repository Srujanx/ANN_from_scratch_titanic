
# 🧠 Neural Network from Scratch — Titanic Dataset

## 📘 Project Overview
This project implements a simple feedforward **neural network (3-2-2-1 architecture)** entirely from scratch using **NumPy**.  
No `sklearn`, no `keras`, no pre-built layers — every forward and backward computation is manually defined.

The goal is to strengthen understanding of **how neural networks actually work under the hood** — from forward propagation to gradient updates — without relying on any deep learning frameworks.

---

## ⚙️ Training Configuration
| Parameter | Value |
|------------|--------|
| Learning Rate | 0.01 |
| Epochs | 500 |
| Loss Function | Binary Cross-Entropy |
| Optimizer | Manual Gradient Descent |

---

## 📊 Results
| Metric | Value |
|---------|--------|
| Training Accuracy | 79.21 |
| Validation Accuracy | 77.65 |

> Results may vary due to random initialization.

---

## 💡 Key Learnings
- Implementing backpropagation manually deepened understanding of gradient flow.  
- Debugging vanishing/exploding gradients built intuition for weight initialization.  
- Reinforced why frameworks like TensorFlow and PyTorch abstract these details.

---

## 🔮 Next Steps
- Implement momentum or Adam optimizer manually  
- Compare manual network vs. sklearn’s `MLPClassifier`  
- Experiment with different activation functions or architectures  

---

## 🧰 How to Run
- git clone https://github.com/srujanx/ANN_from_scratch_titanic.git
- cd ANN_from_scratch_titanic
- pip install numpy pandas matplotlib
- jupyter notebook ANN_Titanic-2.ipynb

---

## 🪪 License
MIT License — free to use, modify, and share.

## 👤 Author
Srujan
Bachelor’s in Artificial Intelligence, Durham College (Canada)
- LinkedIn : www.linkedin.com/in/srujan77
