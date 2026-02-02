# Python for Data Wrangling

A training course covering Python fundamentals for data wrangling using pandas, numpy, and visualization libraries.

## Prerequisites

- Python 3.12

## Installation

### 1. Install uv

[uv](https://docs.astral.sh/uv/) is a fast Python package and project manager.

**macOS/Linux:**
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

**Windows (PowerShell):**
```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

After installation, restart your terminal or run:
```bash
source $HOME/.local/bin/env
```

### 2. Initialize the project

Clone the repository and navigate to the project directory:
```bash
cd training-python-for-data-wrangling
```

Initialize the project:
```bash
uv init
```

Create a virtual environment and install dependencies:
```bash
uv venv
uv pip install numpy pandas matplotlib seaborn bokeh jupyter jupyterlab
```

### 3. Activate the environment

**macOS/Linux:**
```bash
source .venv/bin/activate
```

**Windows:**
```cmd
.venv\Scripts\activate
```

### 4. Launch Jupyter

```bash
jupyter lab
```

This will open JupyterLab in your browser at `http://localhost:8888`. Navigate to the notebook files (`.ipynb`) in the file browser on the left to open them.

## Course Materials

- **Chapter 2**: Data Types - Covers Python data types (integers, floats, strings, lists, tuples, dictionaries, sets, numpy arrays)
- **Chapter 3**: Basic Data Wrangling - End-to-end data wrangling with CSV files using pandas

## Data

The course uses Citibike trip data (`202009CitibikeTripdataExample.csv`) for hands-on exercises.
