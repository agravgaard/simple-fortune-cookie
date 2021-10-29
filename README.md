# Simple Fortune Cookie

## Installation from Day 0

1. Add a self-hosted runner to repository
1. Install `kustomize` on the VM
1. Deploy the database on Kubernetes using the `redis*.yml` manifests
1. Rerun the latest "deploy to k8s"-pipeline on GitHub Actions
1. Wait ? seconds,
    and get the DNS name from `External IP` of the `frontend` service.
