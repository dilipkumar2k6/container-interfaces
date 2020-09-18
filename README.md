# Container Interfaces
Following are standards for Containers 
1. Container Runtime Interface (CRI)
2. Container Network Interface (CNI)
3. Container Storage Interface (CSI)

# Container Runtime Interface (CRI)
## Summary
- The CRI is an integration point between Kubernetes and container runtimes that makes pods (groups of containers) work in Kubernetes clusters. 
- CRI is a plugin interface which enables kubelet to use a wide variety of container runtimes, without the need to recompile. CRI consists of a protocol buffers and gRPC API.

## Reference
https://developer.ibm.com/technologies/containers/blogs/kube-cri-overview/
https://opencontainers.org/
# Container Network Interface (CNI)
## Summary
- CNI (Container Network Interface), a Cloud Native Computing Foundation project, consists of a specification and libraries for writing plugins to configure network interfaces in Linux containers, along with a number of supported plugins. 
- CNI concerns itself only with network connectivity of containers and removing allocated resources when the container is deleted. 
- Because of this focus, CNI has a wide range of support and the specification is simple to implement.
## Reference
https://github.com/containernetworking/cni
# Container Storage Interface (CSI)
## Summary
- The Container Storage Interface (CSI) is a standard for exposing arbitrary block and file storage systems to containerized workloads on Container Orchestration Systems (COs) like Kubernetes. 
- Using CSI third-party storage providers can write and deploy plugins exposing new storage systems in Kubernetes without ever having to touch the core Kubernetes code.

## Reference
https://kubernetes-csi.github.io/docs/
https://www.architecting.it/blog/container-storage-interface/