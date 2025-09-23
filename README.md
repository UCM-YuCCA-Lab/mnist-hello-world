# MNIST Tutorials: Hyperdimensional Computing & PyTorch

This repository provides two step-by-step tutorials for classifying handwritten digits from the MNIST dataset:  

1. **`hd_mnist.ipynb`** – A tutorial using **Hyperdimensional Computing (HDC)**.  
2. **`pytorch_mnist.ipynb`** – A tutorial using a **PyTorch-based Neural Network**.  

Both tutorials are designed for beginners and include detailed explanations to help you understand the workflows.

Because the original MNIST dataset link is broken, we already download the MNIST data in the `mnist_data` folder.

---

## 🚀 Getting Started

Follow these steps to set up the environment and run the notebooks:

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/mnist-tutorials.git
cd mnist-tutorials
```

### 2. Install Miniconda
If you don’t already have it, download and install [Miniconda](https://docs.conda.io/en/latest/miniconda.html), a tool for managing Python virtual environments so you don't mess up with the default system environment.

### 3. Create a conda environment
After you install conda, run the following commands to create a conda environment, activate it and install necessary PyTorch dependencies.
```bash
conda create -n mnist-py39 python=3.9
conda activate mnist-py39
pip3 install -r requirements.txt
```

### 4. Running Jupyter Notebook
To launch Jupyter Notebook, run:
```bash
jupyter notebook
```

## 📂 Repository Structure
```
mnist-tutorials/
├── mnist_data/               # Folder containing raw MNIST dataset
├── hd_mnist.ipynb            # Hyperdimensional Computing tutorial
├── pytorch_mnist.ipynb       # PyTorch Neural Network tutorial
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation
```

## ✨ Notes

* Both tutorials automatically load MNIST data into the mnist_data/ folder.

* The notebooks are annotated for clarity, making them suitable for undergraduates or anyone new to machine learning and HDC.
