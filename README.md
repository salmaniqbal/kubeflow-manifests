# Kubeflow Manifest

Temporarily adding slightly modified config file that is taken from [Kubeflow Manifests](https://github.com/kubeflow/manifests/archive/v1.0.2.tar.gz).

The modified file is: 

`manifests-1.0.2/istio/oidc-authservice/base/statefulset.yaml`

Line 37, before: `"profile email groups"` -> `"profile email"`