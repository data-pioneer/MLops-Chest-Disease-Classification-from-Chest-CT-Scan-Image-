## MLops-Chest-Disease-Classification-from-Chest-CT-Scan-Image

- This repository implements an MLOps pipeline for classifying chest diseases from chest CT scan images using a VGG16 deep learning model. 
- The project leverages various tools to ensure efficient development, deployment, and monitoring:

- Machine Learning Model: VGG16 pre-trained convolutional neural network (CNN) for image classification.
- Download: Images are downloaded from Google Drive (https://drive.google.com/file/d/1zD6V2BSjrO-QWwFPpv7s3JaqtemFoL98/view?usp=sharing).
- Version Control: DVC tracks data versions for reproducibility.
- Experiment Tracking & Model Registry:
  * MLflow: Logs experiments, tracks metrics, and stores models for comparison and deployment.
  * Dagshub: Collaboratively manages the MLOps pipeline and integrates with MLflow for experiment tracking.
- CI/CD Pipeline: GitHub Actions automates building, testing, and deployment upon code changes.


## Key Technologies:


## Project Structure:


## Flow Chart of Project Architecture

![MLflow_Chest_Disease_Classification_Project_Architecture](https://github.com/data-pioneer/MLops-Chest-Disease-Classification-from-Chest-CT-Scan-Image-/assets/33811437/a128cac8-8e64-4b9f-bf28-2a2f9d101b6a)

## Workflows of each component updation

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline 
7. Update the main.py
8. Update the dvc.yaml 



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

