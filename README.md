# Wine dataset exploration

The code, plots, and explanations are bundled together as a Jupyter notebook. Only `python` and `pip` are required to run the instructions below.

## 1. Prepare the environment
```bash
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
```

## 2a. Interactively run the notebook
```bash
jupyter notebook wine.ipynb
```

## 2b. Generate the report
```bash
jupyter nbconvert --to html wine.ipynb
```

This will generate the HTML report, which can then be viewed by any browser of your choice, or converted to PDF.
