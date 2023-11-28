To reproduce:

```
##
# Create the cluster on Aruba Cloud.
# Follow this guide to crete the cluster:
# https://kb.cloud.it/cmp/container/kubernetes/creare-cluster-kubernetes.aspx

##
# Env setup

export KUBECONFIG=your-k8s.conf

##
# Download a binary release of the CLI
go get -u -v github.com/vmware-tanzu/sonobuoy

##
# Run the tests

sonobuoy run --mode=certified-conformance
```
