# Use kubernetes to build and orchestrate  your applications and cloud infrastructure
Your run your applications into  a *kubernetes* cluster and you need to build your cloud infrastructure , using the Iinfrastructure as a code is a good solution ( tools like Terraform , Ansible or
some provider Iacc tools like Aws CloudFormation can be so helpful ) ,

on the one hand, we have Infrastructure as Code tools that require an increase in skills to use them well. On the other hand, *kubernetes* is increasingly becoming the standard for running applications.
But what if you have a toolsthat combines all of the above!  With Crossplane “Provision and manage cloud infrastructure and services using kubectl”

[![Crossplane-K8s](doc-images/crossplane-k8s.PNG)](doc-images/crossplane-k8s.PNG)

## Assumptions and Prerequisites
+ Basic hands-on experience with Kubernetes.
+ Up and Running Kubernetes Cluster (e.g GKE, AKS, EKS,..) v1.16 or newer
+ You have kubectl  installed in your local machine.
+ You have Helm installed ,version v3.2.0 or later

## Objectives: what you will learn ?
1. Introduction to the Crossplane Solution
2. How to install Crossplane 
3. How to Connect Crossplane to Microsoft Azure
4. Create and manage cloud resources from Kubernetes with the Crossplane Azure provider's.

Demo available on my medium story : https://medium.com/@saifeddine.segni94/orchestrate-applications-and-cloud-infrastructure-using-kubernetes-and-crossplane-eaa0356834e6
