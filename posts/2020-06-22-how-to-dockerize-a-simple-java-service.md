---
title: How to Dockerize a simple Java service
description: Just a very simple demonstration of how to Dockerize a simple Java service
date: 2020-06-22
tags:
  - Docker
  - Java
layout: layouts/post.njk
---

https://youtu.be/ts7nE6gO2sA

Quick overview of how to Dockerize a very simple Java REST API service. I will use the resulting project in the next videos on Kubernetes, to exemplify how to use the different features of Kubernetes and more specifically how to deploy and configure an application in a Kubernetes cluster.

Useful links:
    - The cool-service Git repo where the sources of this simple service are: https://github.com/learn-alexchiri-com/cool-service
    - The Dropwizard homepage: https://www.dropwizard.io/en/latest/
    - The documentation of the dropwizard-example project that I used as a base for the cool-service (almost identical): https://www.dropwizard.io/en/latest/manual/example.html
    - The location of the cool-service image on Docker Hub: https://hub.docker.com/repository/docker/alexchiri/cool-service
    - Documentation on multi-stage builds: https://docs.docker.com/develop/develop-images/multistage-build/