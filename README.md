# MLOps

### DevOps

<img src="readme/DevOps.png" width="400">

Plan -> Code -> Build -> Test -> Release -> Deploy -> Operate -> Monitor -> Plan ... <br/>

I think.. DevOps's core is the interaction between users and developers. <br/>
This way leads to a successful operation of the software. <br/>
I've seen this approach a lot in industrial engineering. <br/>

### MLOps == ML + DevOps ?

MLOps aims to service ML as a similar to DevOps.<br/>
But, I think MLOps is not just a combination of ML and DevOps. <br/>

Maybe, Diff between MLOps and DevOps comes mostly from ML's data dependence. <br/>
Surely, Data is important to both MLOps and DevOps. <br/>
But I think much more important for MLOps. <br/>

Even if the company that use ML has a very good model's architecture, the performance of the model varies widely depending on whether the datas are well collected or preprocessed. <br/>

<br/>

### My Test Environment

#### Hardware
    [ NVIDIA DGX Station Version 4.12.0 ]
    OS : Ubuntu 18.04.6 LTS
    CPU : Intel(R) Xeon(R) CPU E5-2698 v4 @ 2.20GHz (40 cores)
    GPU : NVIDIA Tesla V100-DGXS-32GB (4 cards)
    RAM : 256GB

####  Software
    Docker : 
    Kubernetes : 
    Python : 3.9.16

<br/><br/><br/>

## Docker - Containerization

#### Build Once, Run Anywhere

Docker is a tool designed to make it easier to create, deploy, and run applications by using containers. <br/>

'Dockerize' is 'Containerize with Docker.' <br/>
It is a way to package software into standardized units for development, shipment and deployment. <br/>

Nowadays, Docker is most popular containerization tool and indispensable for anybody using data. <br/>
So, I think Docker(Dockerize) is the first step for MLOps. <br/>



## Kubernetes - Container Orchestration




<br/><br/><br/><br/><br/><br/><br/><br/>

### Not yet

Kubeflow - ML Toolkit for Kubernetes <br/>
MLFlow - ML Lifecycle Management <br/>
Airflow - Workflow Management <br/>
Tensorflow Extended - ML Platform <br/>
TFX - ML Platform <br/>
Seldon - ML Deployment <br/>
KubeFlow Pipelines - ML Pipelines <br/>
Metaflow - ML Pipelines <br/>
Kubeflow Fairing - ML Training <br/>