# FluxPractice
Repository to practice Flux CD, Istio and Jsonnet


# Flux CD
Prerequisites:
  - Kubernetes cluster (using K3D in this example)
  - Github Access token to the repo
&nbsp;
  
You can check if you have the right Kubernetes cluster setup for Flux by the following command:
  - "flux check --pre"
<br>
### Starting up K3D cluster (you need Docker)
Commands:
  - "k3d cluster create my-cluster --api-port 6550 -p "9999:80@loadbalancer" --agents 2"

This command creates a cluster with 1 server node (control-plane) and 2 agent nodes.

