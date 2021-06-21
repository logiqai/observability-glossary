# Namespace

A namespace is a way to categorize clusters into sub-clusters on the same physical cluster. Namespaces help teams identify and differentiate between Kubernetes clusters that have shared usage among different teams. Namespaces also enable role-based access controls across shared clusters by limiting users and processes to certain namespaces. 

A cluster can support any number of namespaces within it with each namespace being logically separated from the others while still being able to communicate amongst each other. 

Any resource within Kubernetes exists either in the default namespace or a namespace created by a cluster operator. 

## Default Kubernetes namespaces

Kubernetes ships with the following three default namespaces:

- `default`: The `default` namespace is the default location for every Kubernetes resource. All Kubernetes resources are located in this namespace until newer namespaces are created. 
- `kube-public`: The `kube-public` namespace is the default location for public resources. 
- `kube-system`: The `kube-system` namespace is used for Kubernetes components. 