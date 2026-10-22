```markdown
# Artificial Intelligence for Learning (AMSI41AIN)

This repository contains practical laboratory exercises, tutorials, and coursework for the **Artificial Intelligence for Learning** course (AMSI41AIN, Semester 1)[cite: 1].

---

## 📂 Repository Structure

```text
.
└── Notebooks/
    ├── Notebook1_Introduction_to_PyTorch.ipynb    # Guided notebook for PyTorch basics
    └── Notebook1_e20230979.ipynb                  # Completed lab assignment & exercises

```

---

## 🚀 Topics Covered

### Notebook 1: Introduction to PyTorch

* **Tensor Fundamentals:** Creation, initialization (`torch.rand`, `torch.randn`), shapes, and data types.
* **Device Management:** Utilizing CUDA GPUs (`cuda:0`) vs. CPU fallback, setting reproducible seeds (`torch.manual_seed`, `torch.cuda.manual_seed`).
* **Matrix Operations:** Dot products, matrix multiplication (`torch.matmul`, `@`), transpositions, and dimension handling.
* **Shape Manipulation:** Reshaping, squeezing size-1 dimensions (`torch.squeeze`), and dimension reordering (`torch.permute` from `(N, H, W, C)` to `(N, C, H, W)`).
* **Data Processing & Preprocessing:** Flattening image tensors, feature standardization (calculating per-column mean $\mu$ and standard deviation $\sigma$ without explicit loops).

---

## 🛠️ Setup & Requirements

### 1. Prerequisites

Ensure you have Python 3.10+ installed.

### 2. Virtual Environment Setup

Clone the repository and prepare your environment:

```bash
# Clone the repository
git clone [https://github.com/themonarchofdestruction/Artificial-Intelligent-for-Learning.git](https://github.com/themonarchofdestruction/Artificial-Intelligent-for-Learning.git)
cd Artificial-Intelligent-for-Learning

# Create and activate a virtual environment
python -m venv .venv

# On Windows (PowerShell):
.venv\Scripts\Activate.ps1

# On Linux/macOS:
source .venv/bin/activate

```

### 3. Install Dependencies

Install PyTorch and Jupyter:

```bash
pip install torch torchvision torchaudio
pip install jupyterlab ipykernel

```

---

## 💻 Running the Notebooks

1. Launch JupyterLab or open the workspace in Visual Studio Code:
```bash
jupyter lab

```


2. Navigate to the `Notebooks/` directory and open the target `.ipynb` file.


3. Ensure the Jupyter kernel points to your virtual environment (`.venv`).



---

## Preparing by:

* **Course:** AMSI41AIN — Artificial Intelligence


* **Student ID:** e20230979


* **Institution:** Institute of Technology of Cambodia (ITC)



```

```
