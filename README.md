# project-ml-microservice-kubernetes

This project contains everything needed for the project-ml-microservice-kubernetes Udacity project !

[![CircleCI](https://circleci.com/gh/gfalcone/project-ml-microservice-kubernetes/tree/master.svg?style=svg)](https://circleci.com/gh/gfalcone/project-ml-microservice-kubernetes/tree/master)

## How to run python scripts

### Through Docker

To run application through docker, open a terminal and type : 

```bash
./run_docker.sh
```

This will instantiate a docker container with our web application.

To make a prediction call on it, type this in a new terminal : 

```bash
./make_prediction.sh
```

### Through Kubernetes


To run application through Kubernetes, open a terminal and type :

```bash
./run_kubernetes.sh
```

This will instantiate a docker container with our web application.

To make a prediction call on it, type this in a new terminal :

```bash
./make_prediction.sh
```

## Project structure
