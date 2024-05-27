### Force Removes all pods
- ```kubectl get pods | grep ContainerStatusUnknown | awk '{print $1}' | xargs kubectl delete pod```

### Force Removes all pods
- ```kubectl get pods | grep Error | awk '{print $1}' | xargs kubectl delete pod```
#