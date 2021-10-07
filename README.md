#
# Reproducing this web app
To recreate this web app on your own computer, do the following.

### Create conda environment
Firstly, we will create a conda environment called *ml*
```
conda create -n ml python=3.7.9
```
Secondly, we will login to the *ml* environement
```
conda activate ml
```
### Install prerequisite libraries

Download requirements.txt file

```
wget https://raw.githubusercontent.com/timothypesi/ml-auto-app/main/requirements.txt

```

Pip install libraries
```
pip install -r requirements.txt
```
###  Download and unzip contents from GitHub repo

Download and unzip contents from https://github.com/dataprofessor/ml-app/archive/main.zip

###  Launch the app

```
streamlit run app.py
```
