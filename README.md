# YouTube Sentiment Analyzer - Extension
   
   ## 🎯 Overview
   A extension that analyzes YouTube comment sentiment in real-time using Machine Learning.
   
   ## 🚀 Features
   - Fetches up to 500 comments from any YouTube video
   - Sentiment analysis using LightGBM model
   - Interactive visualizations (pie charts, trend graphs, word clouds)
   - Real-time sentiment scoring
   
   ## 🛠️ Tech Stack
   - **Frontend**: JavaScript, HTML5, CSS3, Extension API
   - **Backend**: Python Flask, deployed on Render
   - **ML**: LightGBM, scikit-learn, NLTK, TF-IDF
   - **Visualization**: Matplotlib, WordCloud, Seaborn
   
   ## 📸 Screenshots
<img width="855" height="564" alt="{827601BD-6BA9-4951-BC1B-77916C08F783}" src="https://github.com/user-attachments/assets/3bee8387-cb78-4c00-b0c5-ece321b1ac7c" />
<img width="840" height="699" alt="{E40D5A10-4364-4880-9658-F6694E74BC8C}" src="https://github.com/user-attachments/assets/915de30d-ba9e-426e-8d14-25a1b2c2ddcb" />
<img width="872" height="730" alt="{97882A58-0F00-4AC6-9857-8B045D5F42F7}" src="https://github.com/user-attachments/assets/46a6d49e-1b3d-40a2-8682-036e8a54d997" />
   
   ## 🔧 Installation
   1. Clone this repository
   2. Open Chrome → Extensions → Enable Developer Mode
   3. Click "Load unpacked" → Select the extension folder
   4. Visit any YouTube video and click the extension icon
   
   ## 📊 Demo
   [https://jumpshare.com/s/e4roADZdkHUeJxKyXsXG]


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

```bash
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
```

## 3. Create ECR repo to store/save docker image
```bash
- Save the URI: 
```

## 4. Create EC2 machine (Ubuntu)
## 5. Open EC2 and Install docker in EC2 Machine:
```bash
#optinal

sudo apt-get update -y

sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker
```

## 6. Configure EC2 as self-hosted runner:
```bash
setting>actions>runner>new self hosted runner> choose os> then run command one by one
```

## 7. Setup github secrets:
```bash
AWS_ACCESS_KEY_ID=

AWS_SECRET_ACCESS_KEY=

AWS_REGION = us-east-1

AWS_ECR_LOGIN_URI = 

ECR_REPOSITORY_NAME = simple-app
```
