# Azure Dev Environment

Just add the following `config.json` file to the root directory to be able to connect to your Azure workspace:
```json
{
  "subscription_id": "YOUR SUBSCRIPTION ID",
  "resource_group": "YOUR RESOURCE GROUP",
  "workspace_name": "YOUR WORKSPACE"
}
```

Containerised dev environment for Azure SDK

This version is based on [this blog post](https://blog.devgenius.io/work-locally-with-azure-machine-learning-from-docker-image-2c2e6884a3e8)