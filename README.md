# Introduction to GitOps with OpenShift

## Purpose

Argo CD is declarative GitOps CD for Kubernetes/OpenShift. This repository contains `deploy.sh`, which - as the name suggests - helps you to deploy ArgoCD on OpenShift.

## What is GitOps

GitOps in short is a set of practices to use Git pull requests to manage infrastructure and application configurations. Git repository in GitOps is considered the only source of truth and contains the entire state of the system so that the trail of changes to the system state are visible/auditable/verifible/reviewable.

## What is ArgoCD

ArgoCD follows the `External Resource Reconcile` pattern, it has a central UI that can orchestrate one to many clusters and multiple Git repositories. One weakness is that if ArgoCD goes down, application management cannot be done.

## License

MIT

## Contributors

Lucian Maly <<lucian@redhat.com>>

---

_Last update: Wed Mar 4 04:37:58 UTC 2020_
