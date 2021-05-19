[![Artifact HUB](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/mirantis)](https://artifacthub.io/packages/search?repo=mirantis)

# NGINX

[NGINX](https://nginx.org) (pronounced "engine-x") is an open source reverse proxy server for HTTP, HTTPS, SMTP, POP3, and IMAP protocols, as well as a load balancer, HTTP cache, and a web server (origin server).

## TL;DR

```bash
$ helm repo add mirantis https://charts.mirantis.com
$ helm install my-release mirantis/nginx
```

## Introduction

Mirantis charts for Helm are carefully engineered, actively maintained and are the quickest and easiest way to deploy containers on a Kubernetes cluster that are ready to handle production workloads.

This chart bootstraps a [NGINX Docker Community](https://github.com/nginxinc/docker-nginx) deployment on a [Kubernetes](http://kubernetes.io) cluster using the [Helm](https://helm.sh) package manager.

## Prerequisites

- Kubernetes 1.12+
- Helm 3.0-beta3+

## Installing the Chart

To install the chart with the release name `my-release`:

```bash
$ helm repo add mirantis https://charts.mirantis.com
$ helm install my-release mirantis/nginx
```

These commands deploy NGINX Docker Community on the Kubernetes cluster in the default configuration.

> **Tip**: List all releases using `helm list`

## Uninstalling the Chart

To uninstall/delete the `my-release` deployment:

```bash
$ helm delete my-release
```

The command removes all the Kubernetes components associated with the chart and deletes the release.
