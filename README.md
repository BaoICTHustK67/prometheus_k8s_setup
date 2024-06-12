# VDT Prometheus Deployment using Prometheus-operator
## Name: Hoang Ba Bao
- Apply the first folder prometheus_operator to install the operator first
  - When apply crds thì sẽ dùng: kubectl apply --server-side -f prometheus-operator/crds     
- Then using mkdir -p /mnt/data/prometheus-main in your workernode to create a mount path that will be use by PersistenceVolume
- Apply prometheus folder to complete setup
