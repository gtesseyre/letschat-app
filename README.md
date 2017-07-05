# letschat-app
Application running on Kubernetes demo using Let's chat app (https://github.com/sdelements/lets-chat) 

This repo contains YAML files describing the deployments and services necessary for the frontend/app part and the MongoDB part

### Instructions 

Clone this repo 
```
git clone https://github.com/gtesseyre/letschat-app.git
cd letschat-app
```
Deploy MongoDB
```
kubectl create -f mongo-deployment-svc.yaml
```
Deploy Let's Chat app 
```
kubectl create -f demochat-deployment-svc.yaml
```
