# Machine Learning - Epitech Tek5 Project

Machine Learning project for Epitech PGE 5th year, covering supervised and unsupervised learning techniques.

## Environment Setup

### Prerequisites

- Python 3.8 or higher
- pip package manager
- Git

### Installation Steps

1. Clone the repository

```bash
git clone <repository-url>
cd Machine-Learning
```

2. Create a virtual environment

macOS/Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

3. Install dependencies

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### Main Dependencies

- NumPy & Pandas: Data manipulation
- Scikit-learn: Machine Learning algorithms
- PyTorch & Torchvision: Deep Learning (exercise 1.2.3)
- Matplotlib & Seaborn: Data visualization
- Jupyter: Interactive notebooks

## Running Notebooks

1. Start Jupyter Notebook

```bash
jupyter notebook
```

2. Navigate to exercices folder and open any .ipynb file

3. Run cells using Shift + Enter

## PyTorch Installation

For Apple Silicon (M1/M2):

```bash
pip install torch torchvision
```

For NVIDIA GPU (CUDA):

```bash
pip install torch torchvision --index-url https://download.pytorch.org/whl/cu118
```

Visit pytorch.org for system-specific installation instructions.

## Datasets

Part 1: Built-in datasets (scikit-learn, generated data)

Part 2: External datasets included in repository

- Exercise 2.1: exercices/2.1/real_drug_dataset.csv
- Exercise 2.2: exercices/2.2/Housing.csv

## Exercises Overview

### 1.1 - Elementary Tools

- Artificial dataset generation
- Metrics definition
- Law of large numbers

### 1.2 - Supervised Learning

- 1.2.1: Binary classification (Basketball game prediction)
- 1.2.2: Regression (Windfarm electricity production)
- 1.2.3: Deep Learning optimization (MNIST speed improvement)

### 1.3 - Unsupervised Learning

- Clustering
- Dimensionality reduction

### 2.1 - Drug Treatment Classification

Multi-class classification to predict treatment effectiveness (Poor/Moderate/Good)

### 2.2 - House Pricing Regression

Regression to predict residential property prices

## Troubleshooting

Module not found:

```bash
pip install <module-name>
```

Jupyter kernel issues:

```bash
python -m ipykernel install --user --name=venv
```

Clear notebook output:

```bash
jupyter nbconvert --clear-output --inplace exercices/**/*.ipynb
```

## Authors

Epitech PGE 5th year - Machine Learning Module 2025-2026

## License

Educational project for Epitech
