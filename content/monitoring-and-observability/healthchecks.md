---
title: Healthchecks
---

## Readiness Probes

Readiness refers to the ability of the application to serve traffic. Readiness cuts off requests without killing the container immediately. [Source](https://kubernetes.io/docs/tasks/configure-pod-container/configure-liveness-readiness-probes/#define-readiness-probes)

## Liveness Probes

Liveness is centered around application state. Liveness cuts off requests and additionally begins a graceful shut down of the container. [Source](https://kubernetes.io/docs/tasks/configure-pod-container/configure-liveness-readiness-probes/#define-a-liveness-command)