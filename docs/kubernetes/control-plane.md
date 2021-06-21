# The Kubernetes control plane

The control plane is responsible for controlling the cluster. Acting as the nerve center of a Kubernetes cluster, the control plane manages the cluster state and configuration data. The control plane components ensure that your containers run in adequate numbers along with all the necessary resources.

## Key components of the Kubernetes Control Plane

The Kubernetes control plane consists of the following key components:

- `etcd`: `etcd` consists of configuration information and data about a Kubernetes cluster's state. 
- `kube-controller-manager`: The `kube-controller-manager` is responsible for running the cluster and controlling its functions. It ensures that the correct number of pods are running at all times. In case a pod goes down, the controller immediately notices it and takes the necessary action.
- `kube-scheduler`: The `kube-scheduler` takes care of the cluster's health. It determines whether your cluster needs new containers and provisions them accordingly, thereby ensuring that your pod's resource needs are met at all times.
- `kube-apiserver`: The `kube-apiserver` is the front-end of the control plane that handles external and internal requests. The `kube-apiserver` determines the validates requests and sends them for processing.

## Also see

- [How to secure your Kubernetes control plane and node components](https://logiq.ai/wp-content/uploads/2021/05/How-to-secure-your-Kubernetes-control-plane-and-node-components.pdf)