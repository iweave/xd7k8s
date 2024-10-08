---
title: Building out a kubernetes environment
layout: page
---

See related posts at [blog.skillcadet.com](https://blog.skillcadet.com)
* [Cloud-init.yaml for k8s node](https://blog.skillcadet.com/2024/10/01/cloud-init-k8s-node.html)

## Included files

### cloud-init-ubuntu2404-k8s130-PGP.yaml
This version is for:
  * Default hostname
  * Ubuntu 24.04
  * Kubernetes 1.30
  * Hard coded apt PGP keys

### cloud-init-ubuntu2404-k8s130-PGP-xd7inode01.yaml
This version is for:
  * A specific hostname
  * Ubuntu 24.04
  * Kubernetes 1.30
  * Hard coded apt PGP keys

### cloud-init-ubuntu2404-k8s130-PGP-withproxy-xd7inode01.yaml
This version is for:
  * A specific hostname
  * Ubuntu 24.04
  * Kubernetes 1.30
  * Hard coded apt PGP keys
  * Using a http proxy host to access resources

### cloud-init-ubuntu2404-k8s130-url-xd7inode01.yaml
This version is for:
  * A specific hostname
  * Ubuntu 24.04
  * Kubernetes 1.30
  * Hard coded apt keyserver urls and keyids

### cloud-init-ubuntu2404-proxy-xd7tower.yaml
This version is for:
  * A specific hostname
  * Ubuntu 24.04
  * Privoxy forward proxy server
  * NGINX reverse proxy server
