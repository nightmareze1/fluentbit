kubectl create namespace logging
kubectl create -f ./fluent-bit-configmap.yaml
kubectl create -f ./es-proxy-deployment.yaml
kubectl create -f ./es-proxy-service.yaml
kubectk create -f ./fluent-bit-ds.yaml
