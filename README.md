# Arewa Data Science Assignment of Saudatu

This repository contains my assignments, practice exercises, Jupyter notebooks, and learning projects completed as part of the **Arewa Data Science Academy** program.

The repository documents my progress as I develop practical skills in Python programming, data analysis, data science, and machine learning.

## About the Repository

The purpose of this repository is to organize and track my learning activities throughout the Arewa Data Science Academy program.

Each week's work is documented in its corresponding notebook, together with supporting Python files and project configuration files.

## Repository Structure

```text
Arewa-Data-Science-Assignment-of-Saudatu/
│
├── .venv/
│   └── Python virtual environment
│
├── notebook-practice/
│   └── Additional Jupyter notebooks and practice exercises
│
├── src/
│   └── Python source code
│
├── week1.ipynb
│   └── Week 1 assignments and Python fundamentals
│
├── week2.ipynb
│   └── Week 2 assignments and practice exercises
│
├── .python-version
│   └── Project Python version
│
├── pyproject.toml
│   └── Project configuration and dependencies
│
├── uv.lock
│   └── Locked project dependencies
│
└── README.md
    └── Project documentation
```

## Weekly Assignments

### Week 1

The Week 1 notebook focuses on Python programming fundamentals and basic problem-solving.

Topics covered include:

* Variables and constants
* Python data types
* Strings
* Comments and docstrings
* Arithmetic operators
* Operator precedence
* Integer division (`//`)
* Modulo (`%`)
* Input and output
* Type conversion
* Rounding
* Mathematical calculations
* Basic Python problem solving

Examples include VAT calculations, time conversion, percentages, averages, perimeter calculations, string manipulation, and mathematical functions.

### Week 2

The Week 2 notebook contains the assignments and practical exercises completed during the second week of the program.

The notebook builds on the Python fundamentals introduced in Week 1 and provides further hands-on practice with programming and data science concepts.

Additional topics and exercises will be documented here as the academy progresses.

## Technologies and Tools

The repository uses:

* **Python** - Main programming language
* **Jupyter Notebook** - Interactive programming and data science exercises
* **Pandas** - Data manipulation and analysis
* **NumPy** - Numerical computing
* **Matplotlib** - Data visualization
* **uv** - Python project and dependency management
* **VS Code** - Development environment
* **Git** - Version control
* **GitHub** - Repository hosting

## Getting Started

### Clone the Repository

```bash
git clone <your-repository-url>
```

Navigate into the project directory:

```bash
cd Arewa-Data-Science-Assignment-of-Saudatu
```

### Create the Virtual Environment

Using `uv`:

```bash
uv venv
```

### Activate the Environment

On Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

### Install Dependencies

Install the project's dependencies with:

```bash
uv sync
```

Additional packages can be installed when required:

```bash
uv add pandas numpy matplotlib jupyter ipykernel
```

### Run the Notebooks

The notebooks can be opened directly in **VS Code** or launched using Jupyter:

```bash
uv run jupyter notebook
```

The main notebooks are:

```text
week1.ipynb
week2.ipynb
```

## Jupyter Kernel

A dedicated Jupyter kernel is configured for this project:

```text
Python (Arewa Assignment)
```

It can be installed with:

```bash
uv run python -m ipykernel install --user --name arewa-assignment --display-name "Python (Arewa Assignment)"
```

When opening a notebook in VS Code, select the **Python (Arewa Assignment)** kernel or the project's `.venv` Python interpreter.

## Learning Objectives

The main objectives of this repository are to:

1. Practice Python programming through practical exercises.
2. Build a strong foundation in data science programming.
3. Develop problem-solving and analytical skills.
4. Learn how to work with data using Python libraries.
5. Apply programming concepts to practical assignments.
6. Document my learning progress throughout the Arewa Data Science Academy program.
7. Build practical projects that demonstrate my understanding of data science concepts.

## Progress

| Week   | Notebook      | Focus                                         |
| ------ | ------------- | --------------------------------------------- |
| Week 1 | `week1.ipynb` | Python fundamentals and programming exercises |
| Week 2 | `week2.ipynb` | Further Python and data science practice      |
| Week 3 | Coming soon   | To be updated                                 |
| Week 4 | Coming soon   | To be updated                                 |

This table will be updated as new assignments are completed.

## Future Work

As the program progresses, this repository will be updated with additional notebooks, assignments, exercises, and practical projects.

Future areas may include:

* Advanced Python programming
* Data manipulation with Pandas
* Numerical computing with NumPy
* Data visualization
* Exploratory Data Analysis
* Feature engineering
* Machine learning
* Model evaluation
* Practical data science projects

## Author

**Saudatu**

Arewa Data Science Academy

## License

This repository is primarily intended for learning, practice, and educational purposes.
