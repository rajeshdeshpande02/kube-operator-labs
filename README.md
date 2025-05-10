# kube-operator-labs
A collection of production-grade Kubernetes Operators built with Golang to automate real-world platform engineering tasks. Each operator is self-contained and designed to showcase different controller-runtime patterns and custom resource use cases.

 ## Operators Overview

| Sr No | Operator Name         | Description                                    | Business Value                            |
|-------|-----------------------|------------------------------------------------|-------------------------------------------|
| 1     | namespace-ripper      | A Kubernetes operator that deletes namespaces based on a value, with exception support. | Automates cleanup of stale namespaces, reducing manual effort and saving cluster resources. |
| 2     | mini-reloader      | A lightweight Kubernetes operator that automatically restarts deployments when their referenced ConfigMaps change. | Ensures application pods always reflect the latest configuration without manual intervention |

## Environment 
- Opderator SDK 

    operator-sdk version: "v1.39.2"

- Golang

    go version go1.24.1 linux/amd64

- Docker

    Version: 27.5.1-1

- Kubernetes

    Client Version: v1.32.3

    Kustomize Version: v5.5.0

    Server Version: v1.32.2