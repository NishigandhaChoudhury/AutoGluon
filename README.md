# AutoGluon | Automated Machine Learning Experiments

Exploring the power of **Automated Machine Learning (AutoML)** using [AutoGluon](https://auto.gluon.ai/). This repository contains practical experiments covering tabular machine learning, multimodal learning, time-series forecasting, cross-validation, and model optimization.

The goal is to understand how automated machine learning simplifies model development, training, evaluation, and prediction.

---

## About the Project

This project is a hands-on exploration of AutoGluon, an open-source AutoML framework developed by AWS.

It focuses on experimenting with different machine learning workflows, understanding model behavior, comparing training approaches, and exploring how automated model selection can improve productivity.

## Project Structure

```text
AUTOGLUON/
│
├── Cross Validation/
│   ├── AutoGluonModels/
│   └── Exp1.ipynb
│
├── MULTIMODEL/
│   ├── Multimodal tutorial files/
│   ├── AutoGluonModels/
│   └── demo.ipynb
│
├── OVERFITTING & UNDERFITTING/
│   ├── AutoGluonModels/
│   └── Exp2.ipynb
│
├── TABULARPOC/
│   ├── AutoGluonModels/
│   └── demo.ipynb
│
├── TIME-SERIES/
│   ├── Time-series tutorial files/
│   └── demo.ipynb
│
├── LICENSE
└── README.md
```

## Experiments and Topics

### 1. Cross Validation
Exploring cross-validation techniques to understand model reliability, validation strategies, and generalization performance.

### 2. Multimodal Machine Learning
Experimenting with AutoGluon's multimodal capabilities and exploring learning from different types of data.

### 3. Overfitting and Underfitting
Understanding the behavior of machine learning models, identifying overfitting and underfitting, and exploring model generalization.

### 4. Tabular Machine Learning
Working with structured datasets using AutoGluon TabularPredictor to automate model training and prediction.

### 5. Time-Series Forecasting
Exploring automated forecasting workflows using AutoGluon's TimeSeriesPredictor.

---

## Tech Stack

| Technology | Purpose |
|---|---|
| Python | Programming language |
| AutoGluon | Automated Machine Learning |
| Pandas | Data manipulation |
| NumPy | Numerical computing |
| Scikit-learn | Machine learning utilities |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Experimentation |
| VS Code | Development environment |

## Getting Started

### Prerequisites

- Python
- Git
- Jupyter Notebook or Visual Studio Code

### 1. Clone the repository

```bash
git clone https://github.com/NishigandhaChoudhury/AutoGluon.git
```

### 2. Navigate to the project

```bash
cd AutoGluon
```

### 3. Create a virtual environment

```bash
python -m venv .venv
```

### 4. Activate the environment

**Windows:**

```powershell
.venv\Scripts\activate
```

**macOS / Linux:**

```bash
source .venv/bin/activate
```

### 5. Install AutoGluon

```bash
python -m pip install --upgrade pip
pip install autogluon
```

Some multimodal and time-series experiments may require additional dependencies. Refer to the [official AutoGluon installation guide](https://auto.gluon.ai/stable/install.html).

### 6. Run the notebooks

Open the relevant `.ipynb` files in VS Code or Jupyter Notebook.

Select your Python environment and execute the notebook cells.

---

## Learning Objectives

- Understand Automated Machine Learning workflows.
- Explore automated model selection and training.
- Experiment with tabular and multimodal machine learning.
- Understand cross-validation and model evaluation.
- Analyze overfitting and underfitting.
- Explore time-series forecasting.
- Develop practical experience with AutoGluon.

## Repository Highlights

- Hands-on Jupyter Notebook experiments.
- Multiple AutoGluon use cases.
- Practical model training and evaluation.
- Exploration of different machine learning approaches.
- Organized experiments by learning topic.

## Contributions

Suggestions, improvements, and contributions are welcome!

If you find an issue or have ideas for improving the experiments:

1. Fork this repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

## License

This project is distributed under the license specified in the [LICENSE](LICENSE) file.

---

## Author

**Nishigandha Choudhury**

GitHub: [@NishigandhaChoudhury](https://github.com/NishigandhaChoudhury)

---

⭐ If you find this repository useful, consider giving it a star!

**Exploring, experimenting, and learning Automated Machine Learning with AutoGluon.**