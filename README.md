# Age-Height ML Analysis

A simple machine learning project that explores the relationship between age and height using linear regression.

## Dataset

`dummy_age_height_dataset.csv` — contains two columns:
- **Age** — person's age
- **Height_cm** — height in centimetres

## What the Notebook Does

`analysis.ipynb` walks through a standard ML workflow:

1. **Import libraries** — pandas, numpy, scikit-learn, matplotlib
2. **Load & inspect data** — read the CSV and preview rows
3. **EDA** — check shape, data types, and missing values
4. **Feature prep** — separate features (`Age`) and target (`Height_cm`)
5. **Visualisation** — histograms for age and height distributions

## Setup

### Prerequisites

- Python 3.9+
- pip

### Install Dependencies

```bash
# Create and activate a virtual environment (recommended)
python -m venv .venv

# Windows
.venv\Scripts\activate

# macOS / Linux
source .venv/bin/activate

# Install packages
pip install -r requirements.txt
```

### Run the Notebook

Open `analysis.ipynb` in VS Code or Jupyter and run the cells sequentially.

## Project Structure

```
├── analysis.ipynb                # Main analysis notebook
├── dummy_age_height_dataset.csv  # Dataset
├── requirements.txt              # Python dependencies
└── README.md                     # This file
```
