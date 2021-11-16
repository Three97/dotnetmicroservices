# Notes

- Container management is the process of organizing, adding, removing, or updating a significant number of containers.
- A container orchestrator is a system that automatically deploys and manages containerized apps.

## Kubernetes

- is a portable, extensible open-source platform for managing and orchestrating containerized workloads
- abstracts away complex container management tasks
- provides you with declarative configuration to orchestrate containers in different computing environments
- The second portion then defines that the container will run as a Kubernetes ClusterIP. ClusterIPs are only accessible from other services running from within the same Kubernetes cluster.

## Minikube

- run `minikube dashboard` to get a sweet view of what's going on (NOTE: I don't know what's going on)

## Issues

- Had problem running `kubectl`, getting an error.
- Reinstalled kubernetes using this page: https://kubernetes.io/docs/tasks/tools/install-kubectl-macos/
- Installed `minikube` using this page: https://minikube.sigs.k8s.io/docs/start/
