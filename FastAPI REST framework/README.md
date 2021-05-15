# Deploying a Deep Learning model
 
## Introduction
This example illustrates the process of deploying an already trained Deep Learning model. To do so, we will take advantage of the user-friendly library fastAPI that provides a nice REST API framework.
 
```
.
└── Root of repo/
    └── FastAPI REST framework (this directory)
        ├── images (includes some images from ImageNet)
        ├── server.ipynb
        ├── client.ipynb
        └── requirements.txt (python dependencies)
```
 
### 1. Installing dependencies using PIP 
 
Before proceeding, double check that you are currently on the `FastAPI REST framework` directory, which includes the `requirements.txt` file. This file lists all the required dependencies and their respective versions. Now use the following command to install the required dependencies:
 
```bash
pip install -r requirements.txt
```
