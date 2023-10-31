# helm

Reference charts meant for sketchy development deployments

### Usage

Login to cluster with `kubectl` or `oc`

```bash
# example: deploy to kubernetes
helm install <release-name> <chart>{./elasticsearch} --values elasticsearch/values.yaml 

# make changes to chart
helm upgrade elasticsearch ./elasticsearch/ --values elasticsearch/values.yaml -f elasticsearch/values.yaml 
```
