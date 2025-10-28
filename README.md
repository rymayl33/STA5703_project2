# STA5703_project2

AI tools were used to assist with syntax suggestions and code cleanup.
This project primarily uses existing libraries; no custom algorithms were developed.

## Download Dataset
Download the maize dataset SAS file found at https://www4.stat.ncsu.edu/~boos/var.select/maize.html

## Set up Virtual Environment
To run this code you first have to create a virtual enviroment and download the dependencies:
```bash
conda create -n myenv python=3.10
conda activate myenv
pip install -r requirements.txt
```

## Running Code
After installing the dependencies you can run the cells in regression_analysis.ipynb to perform regression analysis on the superconductivity dataset.