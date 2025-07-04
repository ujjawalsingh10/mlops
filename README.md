# mlops

### creating and activating env
python -m venv mlflow_env - create
source mlflow_env/bin/activate - load env

pip install pipreqs
pipreqs . ## to get only used dependencies

## MLflow
mlflow ui - used to open mlflow ui in browser

mlflow ui --backend-store-uri sqlite:///mlflow.db  - mlflow backend

#### logging model
`log model as an artifact`
mlflow.log_artifact('mymodel', artifact_path = 'models/')
`log model using log_model`
mlflow.<framework>.log_model(model, artifact_path = 'models/')
