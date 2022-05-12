# Azure Dev Environment
Containerised dev environment for Azure SDK

# How to use
1. Add the following `config.json` file to the root directory to be able to connect to your Azure workspace:
```json
{
  "subscription_id": "YOUR SUBSCRIPTION ID",
  "resource_group": "YOUR RESOURCE GROUP",
  "workspace_name": "YOUR WORKSPACE"
}
```

1. Run `test_nb.ipynb` to connect to your workspace.


This version is based on [this blog post](https://blog.devgenius.io/work-locally-with-azure-machine-learning-from-docker-image-2c2e6884a3e8)