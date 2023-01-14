Deploy a simple Web App with Mongodb database using kubernetes

Commands to run
```
kubectl apply -f mongo-config.yaml
kubectl apply -f mongo-secret.yaml
kubectl apply -f mongo.yaml
kubectl apply -f webapp.yaml
```

See the status of pods
```kubectl get pods```

To get the ip address for app
```minikube ip```

The page should be accessible in the port 30100 in the above ip address