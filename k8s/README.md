

## Kubernetes
- create,add,remove,update containers

Container management is the process of **organizing**, **adding**, **removing**, or **updating** a significant number of **containers**.

- auto scaling and rolling update

A container orchestrator is a system that **automatically** **deploys** and manages containerized apps. As part of management, the orchestrator handles scaling dynamic changes in the environment to increase or decrease the number of deployed instances of the app. It also ensures all deployed container instances are updated when a new version of a service is released.

Kubernetes is a **portable**, **extensible** open-source platform for your management and orchestration of containerized **workloads**. Kubernetes simplifies complex container-management tasks and provides you with **declarative** configuration to orchestrate containers in different computing environments.


### Benefits
- self-healing
- auto scaling
- rolling update
- storage management
- network management
- secrets management

### Control Panel, Nodes, Pods
A cluster uses centralized software that's responsible for **scheduling** and **controlling** these tasks. The computers in a cluster that **run** the tasks are called nodes, and the computers that run the **scheduling** software are called control planes.

A Kubernetes cluster contains at least one main plane and one or more nodes. Both the control planes and node instances can be 
- physical devices, 
- virtual machines, 
- instances in the cloud. 
The default host OS in Kubernetes is Linux, with default support for Linux-based workloads.


The Kubernetes **control plane** in a Kubernetes cluster runs a collection of services that **manage the orchestration functionality** in Kubernetes.

A **node** in a Kubernetes cluster is where your compute workloads run. Each node communicates with the control plane via the API server to inform it about state changes on the node.

A pod represents a single instance of an app running in Kubernetes. The workloads that you run on Kubernetes are containerized apps. Unlike in a Docker environment, you can't run containers directly on Kubernetes. **You package the container into a Kubernetes object called a pod**. A pod is the **smallest** object that you can create in Kubernetes. **A single pod can hold a group of one or more containers**. However, a pod **typically** doesn't contain multiples of the same app.

<p align="center"><img style="display: block; width: 600px; margin: 0 auto;" src=img/2024-03-06-19-41-49.png alt="no image found"></p>



### Reference
- [Microsoft Introduction to Kubernetes](https://learn.microsoft.com/en-us/training/modules/intro-to-kubernetes/)