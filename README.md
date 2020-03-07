# Build and Push a Docker Image to AWS ECR

[![CircleCI](https://circleci.com/gh/daumie/circleci-ecr-orb-demo.svg?style=svg)](https://circleci.com/gh/daumie/circleci-ecr-orb-demo)

A simple project to show the power of using orbs. CircleCI Orbs are shareable packages of configuration elements, including jobs, commands, and executors.

## CirleCI Article Link

[CircleCI article link](https://circleci.com/blog/automatically-deploy-private-docker-images-to-aws-ecr/)


### To understand container registries; Docker registries, we have to take a step back. We need to understand the following:

**Docker** - A software platform for building applications based on containers

**Container** - A method of virtualization that packages an application's code, configurations, and dependencies into building blocks for consistency, efficiency, productivity, and version control.

**Container Image** - A self-contained piece of software that has everything in it needed to run – code, tools, and resources.

**Container image repository** - A collection of named, related container images, usually providing different versions of the same application or service identified by their tags.

A **docker container image registry** is a service that stores container images and is hosted either by a third-party or as a public/private registry such as Docker Hub, AWS(ECR), GCP(GCR), Quay, and so on. This simplifies your development to production workflow.

**Container orchestrator** - Container orchestration is all about managing the lifecycles of containers, especially in large, dynamic environments.
