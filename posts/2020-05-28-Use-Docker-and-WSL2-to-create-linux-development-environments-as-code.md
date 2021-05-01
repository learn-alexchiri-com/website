---
title: Use Docker and WSL2 to create Linux development environments as code
description: Showing a way to define development environments as code for WSL2 using Docker
date: 2020-05-28
tags:
  - DevOps
  - Linux
  - WSL2
  - Docker
layout: layouts/post.njk
---

<br/>
<br/>
{% set videoTitle = "Use Docker and WSL2 to create Linux development environments as code" %}
{% set videoId = "S3m59_lTAuc" %}
{% include 'youtube.njk' %}

In the [Everything-as-code video](https://learn.alexchiri.com/posts/2020-05-28-everything%20as%20code/) I mentioned creating development environments as code as well. Here I show a way to do that using Docker and WSL2 in Windows 10.

* GitHub repo for my POC of using Dockerfiles to create #WSL2 distros: https://github.com/alexchiri/project-dev-palace - very much WIP so no docs for now and the repo is heavily customised for my use, but I plan to change this soon!
* I mentioned the VS Code extension that allows you to use Docker containers as development environments, you can find its docs [here](https://code.visualstudio.com/docs/remote/containers)

Check out [part 2](https://learn.alexchiri.com/posts/2020-05-31-simpler-dev-environments-as-code-with-WSL2-and-acr-tasks/) of this video, where I show an attempt to continuously integrate changes made to these Dockerfiles and semi-automatically update the development environments based on those Dockerfiles running on my computer.