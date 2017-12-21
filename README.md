Deploy prometheus in kubernetes

 kubectl create cm prometheus-config -n kube-system --from-file=prometheus.yaml=prometheus-config.yaml 
kubectl create cm prometheus-rules --from-file=admin.rule=prometheus-rules.yaml -n kube-system

