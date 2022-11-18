# CentOS 7 Docker container for running Azure playbooks.

[![CI](https://github.com/swerveshot/az-ansible-centos7/workflows/Build/badge.svg?branch=main&event=push)](https://github.com/swerveshot/az-ansible-centos7/actions?query=workflow%3ABuild) [![Docker pulls](https://img.shields.io/docker/pulls/swerveshot/az-ansible-centos7)](https://hub.docker.com/r/swerveshot/az-ansible-centos7/)

Created from build instructions on Microsoft Azure developer documentation as can be found here:
https://learn.microsoft.com/en-us/azure/developer/ansible/configure-in-docker-container#create-a-dockerfile-that-will-install-ansible

## How to Use
Use these environment variables to authenticate to Azure.

```bash
export AZURE_TENANT="<azure_tenant_id>"
export AZURE_SUBSCRIPTION_ID="<azure_subscription_id>"
export AZURE_CLIENT_ID="<service_principal_app_id>"
export AZURE_SECRET="<service_principal_password>"
```
