# kube-operator-labs
A collection of production-grade Kubernetes Operators built with Golang to automate real-world platform engineering tasks. Each operator is self-contained and designed to showcase different controller-runtime patterns and custom resource use cases.

 ## Operators Overview

| Sr No | Operator Name         | Description                                    | Business Value                            |
|-------|-----------------------|------------------------------------------------|-------------------------------------------|
| 1     | namespace-ripper      | A Kubernetes operator that deletes namespaces based on a value, with exception support. | Automates cleanup of stale namespaces, reducing manual effort and saving cluster resources. |
| 2     | mini-reloader      | A lightweight Kubernetes operator that automatically restarts deployments when their referenced ConfigMaps change. | Ensures application pods always reflect the latest configuration without manual intervention |
| 3     | [Operator Name 3]      | [Description of Operator 3]                                          | [Business Value of Operator 3]                                                |
