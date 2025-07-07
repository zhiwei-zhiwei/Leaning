# CI/CD Pipeline

**My own word**: *Just a pipeline which speed up the code iteration*

get the code, test the code, construct the environment, delpoy the code to Staging, then test code in Stageing, etc. - happened automatically. Then delopy to production manually.

Speed up the updates and changes of a project.

## What is a CI/CD pipeline
  - CI/CD pipelines are a practice focused on improving software delivery throughout the software development life cycle via automation.
    **Focus on improve software delivery via automation**
  - throughout development, testing, production, and monitoring phases of the software development lifecycle **--->** develop higher quality code, faster and more securely

  - CI/CD pipelines have advantages for software organizations that use virtual machines as well as container-based cloud-native applications.
    **quickly integrate updates and changes to code**

## How do CI/CD pipeline relate to DevOps?
> **CI**: refers to continuous integration, which includes building, testing, and merging code.
> 
> **CD**: continuous delivery, which includes automatically releasing software to a repository.\
> $~~~~~~$ continuous deployment, which adds the step of automatically deploying software to production.

A CI/CD pipeline guides the process of software development through a path of building, testing, and deploying code. By automating the processes that support CI/CD, development and operations teams can minimize human error and maintain a consistent process for how software is released. Pipelines can include tools for compiling code, unit tests, code analysis, security, and binaries creation. For containerized environments, pipelines will also include tools for packaging the code into a container image to be deployed across a hybrid cloud.

**Speeding up hopw an idea goes from development to deployment in a production environment where it can provide value to the user.**

## What is Tekton?
**Tekton is a Knative-based framework to create cloud-native CI/CD pipelines quickly.** As a Kubernetes-native framework, Tekton makes it easier to deploy across multiple cloud providers or hybrid environments.
