# Nodes

Nodes are physical or virtual worker machines in your cluster that run applications. Nodes are managed by the Kubernetes control plane and contain all the services required to run Pods. 

The primary components of a node are the container runtime engine, the kubelet, and kubeproxy. 

- The container runtime engine runs containers in your cluster.
- The kubelet is a tiny agent in charge of making sure your nodes and containers are running.
- The kube-proxy facilitates Kubernetes networking services, handling network communications outside and within the cluster.

To learn more about how to secure your node components, download our free ebook on [How to secure your Kubernetes control plane And node components](https://logiq.ai/wp-content/uploads/2021/05/How-to-secure-your-Kubernetes-control-plane-and-node-components.pdf).