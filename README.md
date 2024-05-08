# MLops-Chest-Disease-Classification-from-Chest-CT-Scan-Image-

## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline 
7. Update the main.py
8. Update the dvc.yaml 



## Live matarials docs

## Git commands

```bash
git add .

git commit -m "Updated"

git push origin main
```

## How to run?

```bash
conda create -n chest python=3.8 -y
```

```bash
conda activate chest
```

```bash
pip install -r requirements.txt
```

```bash
python app.py
```


### Mlflow dagshub connection uri

```bash
MLFLOW_TRACKING_URI="https://dagshub.com/data-pioneer/MLops-Chest-Disease-Classification-from-Chest-CT-Scan-Image-.mlflow"
MLFLOW_TRACKING_USERNAME="data-pioneer"
MLFLOW_TRACKING_PASSWORD="dfbf143408af6a87f453866fb9ee6b6fe0bba8a9"
python script.py
```


### RUN from bash terminal or environment variable 

```bash
export MLFLOW_TRACKING_URI=""""

export MLFLOW_TRACKING_USERNAME="""" 

export MLFLOW_TRACKING_PASSWORD=""

```

### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag

