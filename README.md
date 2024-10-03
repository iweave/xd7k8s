---
title: Building out a kubernetes environment
layout: page
---

See related posts at [blog.skillcadet.com](https://blog.skillcadet.com)
* [Cloud-init.yaml](https://blog.skillcadet.com/2024/10/01/cloud-init-k8s-node.html)

## Included files

### cloud-init-ubuntu2404-k8s130-PGP.yaml
This version is for:
  * Default hostname
  * Ubuntu 24.04
  * Kubernetes 1.30
  * Hard coded apt PGP keys

### cloud-init-ubuntu2404-k8s130-PGP-inode01.yaml
This version is for:
  * A specific hostname
  * Ubuntu 24.04
  * Kubernetes 1.30
  * Hard coded apt PGP keys

### cloud-init-ubuntu2404-k8s130-url-inode01.yaml
This version is for:
  * A specific hostname
  * Ubuntu 24.04
  * Kubernetes 1.30
  * Hard coded apt keyserver urls and keyids

