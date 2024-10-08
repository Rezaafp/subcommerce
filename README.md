# Dicoding Collection Dashboard ✨

## Setup Environment - Anaconda
```
conda create --name main-ds python=3.12
conda activate main-ds
pip install -r requirements.txt
```

## Setup Environment - Shell/Terminal
```
mkdir Submission
cd Submission
pipenv install
pipenv shell
pip install -r requirements.txt
```

## Run steamlit app
```
streamlit run dashboard.py
```

## Can't Deploy
```
Data diatas tidak dapat ter-deploy via streamlit dikarenakan size yang terlalu besar
run via lokal dengan "streamlit run dashboard.py"
```