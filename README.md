# Docker MongoDB JS application using helm charts

## Quick Start

```bash
# Run in Docker
helm install mongodb -f mongodb-values.yaml stable/mongodb
helm install nodejs ./nodeapp

# To delete the app
helm uninstall mongodb nodejs

```
