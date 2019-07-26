# ML Stack

## Pre-requisite

- Homebrew
- Python 3.6+

## Install Python via Homebrew
```bash
brew install python
```
- ### Set Python3 as default
```bash
vi ~/.bash_profile
alias python=python3
source ~/.bash_profile
```
- ### Verify Python Version (Expected Python 3.7.4)
```bash
python --version
```

## Install ML Py Libs via PIP3 

Pandas: data extraction and preparation
NumPy: arrays and linear algebra library
Matplotlib: plotting and data visualization
Seabor: data visualization library based on matplotlib
Scikit-learn: best library for classical ML algorithms
Jupyter Notebook: mixing data, code, and plots in one page

```bash
pip3 install numpy
pip3 install pandas
pip3 install matplotlib
pip3 install seaborn
pip3 install scikit-learn
pip3 install jupyter
```

## Open Jupyter Notebook

```bash
jupyter notebook
```
This command will open a web code editor, code inside the green rectangle and evaluate Python code interactively.


