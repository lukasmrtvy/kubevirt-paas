# Info
Kubernetes as a service platform with based on Flatcar OS 

# Installation order

1. Cilium
2. Kube-OVN
3. Kyverno
4. Longhorn
5. Kubevirt
6. CAPK
7. CDI
8. Sveltos

# Usage
## Prerequisities
```
cd resource-cluster/
kustomize build | kubectl apply -f-
```
## Cluster
```
kubectl apply -f cluster.yaml
```