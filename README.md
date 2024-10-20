# chess-disease-classification


### workflows

- Update config.yaml
- Update params.yaml
- Update the entity
- Update the configuration manager in src config
- Update the components
- Update the pipeline
- Update the main.py
- Update the dvc.yaml

```
bash


conda create -n visa python=3.8 -y
```

```
bash

conda activate visa     
```

```
bash
pip install -r requirements.txt

```
```
bash
python app.py
```

```
bash


conda deactivate

```


import dagshub
dagshub.init(repo_owner='satputesaket', repo_name='ml_flow_exp_tracking', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)


  https://dagshub.com/satputesaket/ml_flow_exp_tracking.mlflow


password = '83788bf93f1a3fab1cf48f5c9f07c4ccfda7a2fe'


RUN from bash terminal

export MLFLOW_TRACKING_URI=https://dagshub.com/satputesaket/ml_flow_exp_tracking.mlflow

export MLFLOW_TRACKING_USERNAME=satputesaket 

export MLFLOW_TRACKING_PASSWORD=83788bf93f1a3fab1cf48f5c9f07c4ccfda7a2fe

