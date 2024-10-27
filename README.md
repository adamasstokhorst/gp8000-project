# GP8000 text classification experiment

## Requirements

- Python 3 (3.10 was used)
- These packages and their dependencies:
  - pandas
  - scikit-learn
  - notebook
  - numpy 1.26
    - It is important that numpy 2.x is not installed, as this breaks pandas

## Setting up

- Clone this repository
  - You may need to pass the `--recurse-submodules` to `git clone`
  - If the `autextification2023` directory is missing, initialize the submodule with `git submodule update --init --recursive`
- (Optional) Set up and activate a virtual environment
- Install requirements by running `pip install -r requirements.txt`
- Run Jupyter Notebook with `jupyter notebook`
- Open `main.ipynb`
  - Results from previous execution should still be present
