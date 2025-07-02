# mlops

### creating and activating env
python -m venv mlflow_env - create
source mlflow_env/bin/activate - load env

pip install pipreqs
pipreqs . ## to get only used dependencies

## MLflow
mlflow ui - used to open mlflow ui in browser

mlflow ui --backend-store-uri sqlite:///mlflow.db  - mlflow backend
