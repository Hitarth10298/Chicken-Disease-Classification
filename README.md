# Chicken-Disease-Classification

1. Update config.yaml
2. Update secrets.yaml [optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the dvc.yaml


## Run from terminal for deployment on Azure

docker build -t chickenapplication.azurecr.io/chicken:latest .
docker login chickenapplication.azurecr.io
docker push chickenapplication.azurecr.io/chicken:latest

password : FaKSbJdrM+1/yj1agAzkrvPkpd64RpiL+HbhvyCWrG+ACRCdOYqF