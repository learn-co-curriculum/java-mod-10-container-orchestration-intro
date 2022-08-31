# A Brief Introduction to Container Orchestration

## Learning Goals

- Understanding the needs for Container Orchestration


## Introduction

We've been using Docker up until this point solely for development purposes.

When moving from this development space to production, there are many more considerations that need to be made as to the full lifecycle of a production application.
While a handful of local applications are easily managed with Docker and Docker Compose, environments start becoming unmanageable when that handful changes to dozens or hundreds of applications.

Besides just the increased amount of containers, production environments also need to start planning for network routing, upgrades, auto-scaling, lifecycle management, resource scheduling, performance monitoring, logging, etc.

Manually running production systems with all these integration points quickly becomes impractical, at which point some type of automation is required for managing these containers.

Enter the concept of Container Orchestration, which has the sole purpose of handling all this complexity.


## Basics of Kubernetes

Kubernetes(commonly seen as K8S) is the undisputed winner of the container orchestration race. You may still see references to systems such as Docker Swarm, Mesos, Cattle, and others.
But, almost all new environments use Kubernetes. And, all Cloud providers provide managed Kubernetes instances at this point.

Read the following for an overview of the role Orchestration plays, with a focus on Kubernetes.

- [Orchestration Goals](https://medium.com/@Rancher_Labs/the-three-pillars-of-kubernetes-container-orchestration-247f42115a4a)
- [Kubernetes Overview](https://kubernetes.io/docs/concepts/overview/what-is-kubernetes/)
