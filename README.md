# Fuzzy System Example

This repository contains a Python implementation of a fuzzy inference system (FIS) for evaluating project risks based on `Project Funding` and `Project Staffing`. The system is implemented using the `scikit-fuzzy` library.

---

## Features

- **Input Variables**:
  - `Project Funding`: Evaluates the adequacy of funding with membership functions like `Inadequate`, `Marginal`, and `Adequate`.
  - `Project Staffing`: Assesses staffing levels with membership functions like `Small` and `Large`.

- **Output Variable**:
  - `Project Risk`: Determines the level of risk with membership functions like `Low`, `Normal`, and `High`.

- **Fuzzy Rules**:
  - Combines the input variables to evaluate the project risk using expert-defined fuzzy rules.

- **Defuzzification**:
  - Uses the centroid method to calculate the crisp output for project risk.

---

## File Contents

- **Fuzzy_system_example.ipynb**:
  - Jupyter Notebook containing the Python implementation of the fuzzy inference system.
  - Includes the definition of membership functions, fuzzy rules, and defuzzification process.
  - Visualizes input and output membership functions.

---

## Prerequisites

Make sure you have the following installed:

- Python 3.7+
- Required Libraries:
  - `numpy`
  - `matplotlib`
  - `scikit-fuzzy`

To install the libraries, run:
```bash
pip install numpy matplotlib scikit-fuzzy
