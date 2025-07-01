# MyTorch – Neural Network from Scratch

This project is part of the **AI702: Deep Learning** course at MBZUAI. The objective was to build a **fully functional neural network library from scratch**, without using PyTorch or TensorFlow autograd. All computations were done using NumPy.

## 🧠 Features Implemented

- ✅ Linear Layers (`mytorch/nn/linear.py`)
- ✅ Activation Functions: Sigmoid, Tanh, ReLU
- ✅ Loss Functions: MSE Loss, Cross Entropy Loss
- ✅ Stochastic Gradient Descent Optimizer (with optional Momentum)
- ✅ Batch Normalization
- ✅ Fully Connected MLP models with 0, 1, and 4 hidden layers

## 📁 Folder Structure

```
mytorch-mlp/
├── mytorch/
│   ├── nn/                  # Linear, activation, loss, batchnorm
│   └── optim/               # SGD optimizer
├── models/                  # MLP0, MLP1, MLP4 model definitions
├── autograder.py            # Local autograder to test implementations
├── autograder_flags.py
├── requirements.txt
└── README.md
```


## 📦 Installation

### 1. Clone the repository
```bash
git clone https://github.com/h-abid97/rag-chatbot.git
cd rag-chatbot
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```


### 3. Running the Local Autograder
Test your components locally by setting the flags in autograder_flags.py and then running:
```bash
python autograder.py
```

## 📌 Notes
- This project is educational and inspired by PyTorch-style architecture.
- No external deep learning frameworks were used.
- BatchNorm and backpropagation were implemented from scratch.