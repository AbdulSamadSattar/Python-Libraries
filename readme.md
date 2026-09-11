# Python Libraries

## 📚 About Python Libraries

Python libraries are collections of **pre-written, reusable code** that provide functions, classes, and tools for specific tasks. They allow developers to build applications more efficiently without implementing everything from scratch.

I’m a Computer Science graduate currently strengthening my Python skills by exploring commonly used libraries and their practical applications.

This repository contains my **learning notes, examples, and practice programs** as I explore different Python libraries and apply them to real-world programming tasks.

### 🎯 Learning Goals

* Understand commonly used Python libraries
* Learn their core features and practical use cases
* Practice through examples and small projects
* Build a strong foundation for **AI, Machine Learning, and Data Science**
* Develop practical Python programming skills

> **Learning by building, practicing, and improving one library at a time.**

---

# ⚙️ Environment Setup

Before working with the examples in this repository, it is recommended to set up **Jupyter Notebook** and a **Python virtual environment**.

## 🪟 Windows Setup

Open **Command Prompt (CMD)** inside your project folder.

### 1. Check Jupyter Installation

```bash
jupyter --version
where jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

### 2. Create a Virtual Environment

In the CMD opened in your current project folder:

```bash
python -m venv myenv
```

### 3. Activate the Virtual Environment

**PowerShell:**

```powershell
myenv\Scripts\Activate.ps1
```

**Command Prompt:**

```cmd
myenv\Scripts\activate.bat
```

After activation, you should see `(myenv)` at the beginning of your terminal prompt.

### 4. Install Jupyter and IPyKernel

```bash
pip install jupyter ipykernel
```

Register the virtual environment as a Jupyter kernel:

```bash
python -m ipykernel install --user --name=myenv --display-name "Python (myenv)"
```

You can now select **Python (myenv)** as the kernel when working in Jupyter Notebook.

---

# 🔢 NumPy

[NumPy](https://numpy.org/) is a fundamental Python library for **numerical computing**. It provides powerful multidimensional arrays and mathematical functions and is widely used in Data Science, Machine Learning, and AI.

### Installation

Make sure the virtual environment is activated:

```powershell
myenv\Scripts\Activate.ps1
```

or:

```cmd
myenv\Scripts\activate.bat
```

Install NumPy:

```bash
pip install numpy
```

### Check Installation

Using Python:

```python
import numpy as np

print(np.__version__)
```

Or directly from the terminal:

```bash
python -c "import numpy; print(numpy.__version__)"
```

---

# 🐼 Pandas

[Pandas](https://pandas.pydata.org/) is a Python library designed for **data manipulation and analysis**. It provides powerful data structures such as `DataFrame` and `Series`, making it easier to work with structured datasets.

### Installation

Activate your virtual environment:

```powershell
myenv\Scripts\Activate.ps1
```

Upgrade `pip`:

```bash
python -m pip install --upgrade pip
```

Install Pandas:

```bash
pip install pandas
```

### Check Installation

```python
import pandas as pd

print(pd.__version__)
```

---

## 🚀 What's Next?

This repository will gradually include more Python libraries, examples, exercises, and practical projects.

The ultimate goal is to use these libraries to develop stronger skills in:

**Python → Data Analysis → Machine Learning → AI Engineering**

> **Learn → Practice → Build → Improve**
