# Cluster monitoring with Promotheus and Grafana

## 
```shell
kubectl create namespace monitoring 
```

## Prometheus
Edit prmetheus.yaml and replace NFS_SERVER_IP with accordingly
```shell
kubectl apply -f prmetheus.yaml 
```

## Grafana (wip)
```shell
kubectl apply -f grafana.yaml 
```