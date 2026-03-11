# End-to-end-ML-Project


## Workflows
1. update config.yaml
2. update schema.yaml
3. update params.yaml
4. update the entity
5. update the configuration manager in src config
6. update the components
7. update the pipeline
8. update the main.py
9. update the app.py


# How to run?
### STEPS:


```bash
conda create -n mlproj python=3.9 -y 
```

```bash
conda activate mlproj
```

```bash
pip install -r requirements.txt
```

```bash
python app.py
```

```bash
Now open up your local host 0.0.0.0:8080
```

# AWS-CICD-Deployment-with-Github-Actions
## 1. Login to AWS console.
## 2. Create IAM user for deployment

#with specific access

1. EC2 access : It is virtual machine

2. ECR: Elastic Container registry to save your docker image in aws


#Description: About the deployment

1. Build docker image of the source code

2. Push your docker image to ECR

3. Launch Your EC2 

4. Pull Your image from ECR in EC2

5. Lauch your docker image in EC2

#Policy:

1. AmazonEC2ContainerRegistryFullAccess

2. AmazonEC2FullAccess