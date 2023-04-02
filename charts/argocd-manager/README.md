# Argo CD Manager ServiceAccount Creator

## Usage

[Helm](https://helm.sh) must be installed and `rtsp/helm-charts` repo must be added.

To install the argocd-manager chart:

`helm install argocd-manager rtsp/argocd-manager -n argocd --create-namespace`
