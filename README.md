cd graphana_prometheus/
ll
kubectl apply -f .
kubectl get ns
# graphana_prometheus
****kubectl expose deployment grafana-deployment --type=NodePort --port=3000 --name=grafana-service --namespace=monitoring

****kubectl get svc -n monitoring
