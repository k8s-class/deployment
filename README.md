# Deployment

### How do we test it to make sure its working?

```
kubectl get pods
kubectl exec -ti helloworld-deployment-67f66c98cc-bm55d -- /bin/bash
curl http://localhost:3000
Hello World!
```
