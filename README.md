# T20I-Score-predictor

## About project
This is a classic Machine learing problem based Regression problem which depends on various inputs to give a output in form a numerical form,in this case in form total score prediction.

## Dataset

The dataset available for this application is present on [dataset](https://www.kaggle.com/datasets/veeralakrishna/cricsheet-a-retrosheet-for-cricket?select=t20s)

## How to run the project
Clone the repository
```bash
https://github.com/saurabhznaikz/t20I-Score-predictor.git
```

Create conda enviornment after creating repository
```bash
conda create -n env python=3.7.10 -y
conda activate env
```
install requirements
```bash
pip install -r requirements.txt
```
run jupyter notebook
```bash
Data Extractor.ipynb
```
This will result in creation of 1 pickle files
```bash
pipe.pkl
```

run streamlit app
```bash
streamlit run app.py
```
