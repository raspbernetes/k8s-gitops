# Kubernetes Cluster Management

https://raspbernetes.github.io/docs/

## Install FluxCD

To install FluxCD use the following installation [script](install/flux.sh).

This will install all required custom resource definitions (CRDs) and deploy the manifests to run flux, it will also use the unofficial raspbernetes image as this supports multi-archiectures.

> Note: If you've forked this repository you will need to update the following to match your own personal account `export GHUSER="raspbernetes"`.

<!-- ## Cluster Components

- kube-system
  - kured
  - metallb
  - metrics-server
  - nginx-ingress
  - oauth2-proxy
  - sealed-secrets
- observability
  - loki
  - prometheus-operator
    - grafana
    - prometheus
  - speedtest
- security
  - cert-manager
  - falco
  - gatekeeper
- serverless
  - openfaas
- storage
  - velero
  - openebs
  - rook-ceph -->

## Contributors

This project exists thanks to all the people who contribute.

<a href="https://github.com/raspbernetes/k8s-gitops/graphs/contributors"><img src="https://opencollective.com/raspbernetes/contributors.svg?width=890&button=false" /></a>
