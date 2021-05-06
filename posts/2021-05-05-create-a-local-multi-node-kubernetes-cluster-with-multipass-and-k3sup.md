---
title: Create a local multi-node Kubernetes cluster with multipass and k3sup
description: Demoing a basic setup of creating a local cluster using multipass and k3sup
date: 2021-05-05
tags:
  - Kubernetes
  - k3s
  - multipass
layout: layouts/post.njk
---

<br/>
<br/>
{% set videoTitle = "Create a local multi-node Kubernetes cluster with multipass and k3sup" %}
{% set videoId = "nkLVgMKk4sQ" %}
{% include 'youtube.njk' %}

Wouldn't it be nice to be able to quickly create a local multi-node #kubernetes​ cluster to play around?

There are some options out there like Docker Desktop that provide a Kuberentes cluster out of the box. But it's usually with one node and you cannot always access the nodes from the host, which can be annoying when learning Kubernetes (for example you cannot access NodePort services).

I am currently experimenting with a setup using #multipass​ and #k3s​ (#k3sup​) which is multi-platform (works on #Windows​, #Linux​ and #macOS​), allows multi-node setups and comes with support for 1 LoadBalancer service out-of-the-box. Pretty great for learning Kubernetes! 🚀

This is a very much work in progress and I only did a very basic bash script for now, should write a Powershell one for Windows.

Let me know in the comments what you think and if you find this useful. I'm planning to post more videos about this.

👀 Mention: while Googling around, I found a way more advanced solution using similar tooling: https://github.com/kubernauts/bonsai​

🔗 Links:
- Project repo: https://github.com/learn-alexchiri-co...​
- Multipass: https://multipass.run​
- k3s: https://k3s.io​
- k3sup: https://github.com/alexellis/k3sup