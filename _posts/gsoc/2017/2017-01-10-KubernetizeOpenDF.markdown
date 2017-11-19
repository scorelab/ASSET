---
layout: gsoc
categories: gsoc2017
divid: opendfkubernetize
title:  OpenDF - Kubernetize OpenDF
description: <p>We have to put all the parts of the OpenDF into Kubernetes  where anyone can deploy OpenDF with all the modules easily.  We have some modules which are not Dockerized, you have to take care of them too. Modules exposes RESTful APIs, they should be made available through an API manager with proper access control mechanism. SSL support also should be there.</p><p>Static files( frontend ) should be served by an NGINX server, which resides on its own container. You can work on this in community bonding period.
githuburl: https://github.com/scorelab/OpenDF
requiredknowledge: Kubernetes, Docker, API Management, SSL
possiblementors: Milindu Sanoj Kumarage(sanoj@scorelab.org)
---