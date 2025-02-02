# ML_Project_MLflow


# How to run:

Clone the repository

### Step 1- create a conda environment after opening the repo
```bash
conda create -n mlproj python = 3.8 -y
```

```bash
conda activate mlproj
```

### Step 2- install the requirements
```bash
pip install -r requirements.txt
```

### Run the following command
```bash
python app.py
```

```bash
open your local host and port
```

## MLflow

[Documentation](https://mlflow.org/docs/latest/index.html)


#### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

import dagshub
dagshub.init(repo_owner='ty875', repo_name='ML_Project_MLflow', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)
python script.py

Run this to export as env variables:

```bash

export MLFLORW_TRACKING_URL

export MLFLORW_TRACKING_USERNAME = 

export MLFLORW_TRACKING_PASSWORD = 

## Workflows

1. Update config.yaml
2. Update schema.yaml
3. Update params.yaml
4. Update entity
5. Update configuration manager in src config
6. Update components
7. Update pipeline
8. Update main.py
9. Update app.py

