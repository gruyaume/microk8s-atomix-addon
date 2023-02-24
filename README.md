# MicroK8s Atomix Addon

[Atomix](https://atomix.io/) provides distributed data structures and coordination primitives for Kubernetes.

This MicroK8s addon makes it easy to deploy and use Atomix on your MicroK8s cluster.

## Usage

```bash
microk8s addons repo add atomix https://github.com/gruyaume/microk8s-atomix-addon
microk8s enable atomix/atomix-runtime
microk8s enable atomix/atomix-raft
```
