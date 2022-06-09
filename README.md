```
helm repo add bitnami https://charts.bitnami.com/bitnami
helm dep build
helm install bugreport .
kubectl port-forward svc/grafana-service 3000:3000
```