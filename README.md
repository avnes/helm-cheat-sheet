# helm-cheat-sheet
Just a bunch of commands that makes my work with Helm easier

## Find the values for a deployed chart

```bash
# 'helm list -A' to find all releases in all namespaces.  
NAMESPACE='' 
RELEASE_NAME=''

helm -n $NS get all $RELEASE_NAME > chart_deployed_values.yaml
```
