---
title: Simpler dev environments as code with WSL2 and ACR Tasks
description: Building on top of the previous video on dev environments-as-code with Docker and WSL2, adding some automation
date: 2020-05-31
tags:
  - DevOps
  - Linux
  - WSL2
  - Docker
layout: layouts/post.njk
---

https://youtu.be/03IqAdwd9NY

Follow-up on previous video on dev environments as-code with WSL2 and Docker (https://learn.alexchiri.com/posts/2020-05-28-Use-Docker-and-WSL2-to-create-linux-development-environments-as-code/). This time, I'm showing an attempt to streamline the building, pushing and updating the environments on the local machines using Azure Container Registry Tasks and a custom profile in Windows Terminal.

Links:
* GitHub repo for my POC of using Dockerfiles to create WSL2 distros: https://github.com/alexchiri/project-dev-palace
* Tutorials on using ACR Tasks to build and push images on commit: https://docs.microsoft.com/en-us/azure/container-registry/container-registry-tutorial-build-task