---
date: 2017-03-22T16:47:24Z
Title: With Docker
tags: ["Tyk Stack", "Self-Managed", "Installation", "Docker"]
description: "How to install the Tyk stack components using Docker in a self-managed environment"
menu:
  main:
    parent: "Installation"
weight: 1
url: "/tyk-on-premises/docker"
aliases:
  - /getting-started/installation/with-tyk-on-premises/docker/
---

Tyk has three containers that are available to set up a Docker installation:

* [The Tyk Gateway container](https://hub.docker.com/r/tykio/tyk-gateway/)
* [The Tyk Dashboard container](https://hub.docker.com/r/tykio/tyk-dashboard/)
* [The Tyk Pump container](https://hub.docker.com/r/tykio/tyk-pump-docker-pub/)

All three are required for a full deployment. We recommend that each container is installed on a separate machine for optimum performance.

We also have a [Docker Tyk Pro Demo](), which installs our full On-Premises Pro solution, which includes our Gateway, Dashboard, and analytics processing pipeline. This demo will run Tyk On-Premises Pro on your machine.