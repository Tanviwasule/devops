# K8s Manifest

This folder contains all Kubernetes YAML files required to run IHR.

## Usage

- To apply the whole manifest:

  ```bash
  kubectl apply -R -f ./manifest
kubectl apply -R -f ./manifest
kubectl delete -R -f ./manifest
10.0.1.12 kafka1
10.0.1.13 kafka2
10.0.1.14 kafka3
10.0.1.20 kafka4
10.0.1.33 kafka5
10.0.1.34 kafka6
kubectl create job --from=cronjob/<cronjob-name> <job-name>
kubectl logs pod/<pod-name> -f
kubectl logs job/<job-name> -f