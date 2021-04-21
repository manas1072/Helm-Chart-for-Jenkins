# Helm-Chart-for-Jenkins
This Chart will provide a Jenkins Setup in the K8S by using the jenkins docker image<br/><br/>
[![Artifact HUB](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/helm-chart-for-jenkins)](https://artifacthub.io/packages/search?repo=helm-chart-for-jenkins)

## What is Helm?<br/>
In simple terms, Helm is a package manager for Kubernetes. Helm is the K8s equivalent of yum or apt. 
Helm deploys charts, which you can think of as a packaged application. 
It is a collection of all your versioned, pre-configured application resources which can be deployed as one unit. 
You can then deploy another version of the chart with a different set of configuration.

## Prerequisites

The following prerequisites are required for a successful and properly secured use of Helm.

1. A Kubernetes cluster
2. Deciding what security configurations to apply to your installation, if any
3. Installing and configuring Helm.

## Initialize a Helm Chart Repository

> helm repo add stable https://charts.helm.sh/stable

## Install an Example Chart

> helm repo update         
> helm install stable/mysql --generate-name

