---
title: How to setup WSL2 and Docker for WSL2 on Windows 10
description: 
date: 2020-05-07
tags:
  - Kubernetes
  - Docker
  - Microservices
  - Windows 10
layout: layouts/post.njk
---

https://youtu.be/Ud0LAss1xRo

A quick tutorial on how to setup #WSL 2 (Windows Subsystem for Linux) and Docker for WSL2 on Windows 10.

Topics covered:
* Enable WSL in Windows 10
* Sign up for the Windows Insider Program
* Install and configure WSL2
* Install a couple of WSL distributions
* Install Docker Desktop with WSL2 backend
* Install and configure the new Windows Terminal (preview)

Useful links shown in the video:
* Slides: https://app.slidebean.com/p/eB09NFC64z/How-to-setup-WSL2-and-Docker-for-WSL2-on-Windows-10
* Official guide from Microsoft on installing WSL2: https://docs.microsoft.com/en-us/windows/wsl/wsl2-install
* Page for downloading updated linux kernel for WSL2: https://docs.microsoft.com/en-us/windows/wsl/wsl2-kernel
* Issue on WSL when trying to update the linux kernel and getting an error that suggests that WSL is not enabled (when in fact it is): https://github.com/microsoft/WSL/issues/5014
* Link to windows tool that can help us uninstall previous version of WSL Linux kernel and allow us to install the updated #Linux kernel for WSL: https://support.microsoft.com/en-us/help/17588/windows-fix-problems-that-block-programs-being-installed-or-removed
* Link to download Docker Desktop for Windows with WSL2 backend: https://docs.docker.com/docker-for-windows/wsl-tech-preview/