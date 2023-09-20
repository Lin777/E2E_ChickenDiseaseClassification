# E2E_ChickenDiseaseClassification

## Workflows

Update config.yaml
Update secrets.yaml [Optional]
Update params.yaml
Update the entity
Update the configuration manager in src config
Update the components
Update the pipeline
Update the main.py
Update the dvc.yaml

## Instalation

1. Clone the repository (git clone git@github.com:Lin777/E2E_ChickenDiseaseClassification.git)
2. Create a python environment and activate it (conda create -n venv python=3.8 -y)
3. Install the requirements (pip install -r requirements.txt)
4. Run the Flask application (python app.py)

## Using DVC for pipeline management

DVC Documentation: https://dvc.org/doc

dvc init 
dvc repro
dvc dag

## Create ECR repo to store/save docker image

- Save the URI: 897355504670.dkr.ecr.eu-north-1.amazonaws.com/chicken
