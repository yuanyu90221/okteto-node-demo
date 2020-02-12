# Getting Started on Okteto with Node.js

This example shows how to leverage [Okteto](https://github.com/okteto/okteto) to develop a Node Sample App directly in Kubernetes. The Node Sample App is deployed using raw Kubernetes manifests.

This is the application used for the [How to Develop and Debug Node.js Applications in Kubernetes](https://okteto.com/blog/how-to-develop-node-apps-in-kubernetes/) blog post.


## switch between different deploy environment

1. local minikube
```shell=
export KUBECONFIG=C:\Users\json\.kube\config
```

2. okteto online

```shell=
export KUBECONFIG=C:\Users\json\.kube\okteto-kube.config
```
