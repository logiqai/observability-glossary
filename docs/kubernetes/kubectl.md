# kubectl

kubectl is Kubernetes' command line tool that lets you control your Kubernetes clusters. You can configure kubectl using a [`kubeconfig`](kubeconfig.md) file named `config` placed in your `$HOME/.kube` directory. 

You can run kubectl commands using the following syntax from a terminal window:

```
kubectl [command] [TYPE] [NAME] [flags]
```
where:

- `command`: is used to specify the operation that you'd like to perform on your Kubernetes resources. 
- `TYPE`: is used to specify the resource type on which you'd like to perform your operation. Examples of resource types are `pods`, `bindings`, `endpoints`, `configmaps`, etc. 
- `NAME`: is used to specify the name of the resource. 
- `flags` is used to specify optional flags such as `-s` or `--server`.

Visit the official Kubernetes documentation sites for detailed explanations of the [syntax](https://kubernetes.io/docs/reference/kubectl/overview/#syntax), [operations](https://kubernetes.io/docs/reference/kubectl/overview/#operations), [resource types](https://kubernetes.io/docs/reference/kubectl/overview/#resource-types), [output options](https://kubernetes.io/docs/reference/kubectl/overview/#output-options), and [examples](https://kubernetes.io/docs/reference/kubectl/overview/#examples-common-operations) of common operations. 

To check out our very own command-line tool for running operations on the LOGIQ Observability platform, visit our [`logiqctl`](https://logiqctl.logiq.ai/) documentation site.

