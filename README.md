# gitops-2
Gitops study project
This repository serves as the GitOps configuration source, containing all Kubernetes manifests and Argo CD application definitions.
Argo CD continuously monitors this repository and the Kubernetes cluster. Whenever a change is made to the manifests—such as updating the Docker image tag in the Deployment file—Argo CD automatically synchronizes the cluster state to match the updated configuration ie. single source of truth.
