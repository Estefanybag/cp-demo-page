# Example Page

## Pre-requirements 📋

_It is recommended to have the following technologies installed_

* [Docker](https://www.docker.com/get-started)
* [Skaffold](https://skaffold.dev/)
* [Kustomize](https://kustomize.io/)
* [Kubectl](https://kubernetes.io/es/docs/tasks/tools/install-kubectl/)

## Installation 🔧

_To run the project you must create an [.envrc](.envrc-example) file with the following environment variables_

```
export PORT=8000

```

_The environment variables created in the .env file must be exported_

```
source .envrc
```
## Deploy 📦
_To run the server with its functionality, you must use the node run command_

```
npm i && node server.js
```


## Deploy Kubernetes 📦

_To run command_

```
skaffold run -p name-profile
```

_To run command_
docker-compose up -d
kubectl get ns
kubectl -n test get all
kubectl -n default get all
