---
title: Reinstall Kyma (Scripts)
type: Installation
---

>**CAUTION**: This document describes a deprecated flow. Follow [this document](/root/kyma/#installation-reinstall-kyma) to install locally using the Kyma CLI.

The custom scripts allow you to remove Kyma from a Minikube cluster and reinstall Kyma without removing the cluster.

> **NOTE:** These scripts do not delete the cluster from your Minikube. This allows you to quickly reinstall Kyma.

1. Use the `clean-up.sh` script to uninstall Kyma from the cluster. Run:
  ```
  scripts/clean-up.sh
  ```

2. Run this script to reinstall Kyma on an existing cluster:
  ```
  cmd/run.sh --skip-minikube-start
  ```
