# GG3: Neural Data Analysis

Undergraduate IIA project, Department of Engineering, University of Cambridge.

## Local environment

Create and activate the project environment from this folder:

```sh
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip setuptools wheel
python -m pip install -r requirements.txt
```

If Matplotlib cannot write to its default cache directory, use a project-local cache:

```sh
export MPLCONFIGDIR="$PWD/.matplotlib"
```

In VS Code or Jupyter, select the Python interpreter at `.venv/bin/python`.
