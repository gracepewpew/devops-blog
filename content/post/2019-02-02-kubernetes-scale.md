---
title: Scaling My Kubernetes Deployment
date: 2019-02-02
tags: ["kubernetes", "code"]
draft: false
---
Copyright © 2019. Packt Publishing, Limited. All rights reserved.
Scaling my Kubernetes deployment
<!--more-->
'''sh
$ kubectl scale deployments/kubernetes-bootcamp --replicas=4
'''
$ kubectl get deployments
$ kubectl get pods -o wide
