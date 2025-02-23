# argocd-gke-dns-endpoint-clusters
Helm Chart to connect ArgoCD to GKE clusters via DNS-EndPoint

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

>  helm repo add argocd-cluster-management https://suryaval.github.io/argocd-gke-dns-endpoint-clusters/

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo argocd-cluster-management` to see the charts.

To install the `argocd-gke-dns-endpoint-clusters`chart:

  >  helm install argocd-gke-dns-endpoint-clusters argocd-cluster-management/argocd-gke-dns-endpoint-clusters

To uninstall the chart:

  >  helm uninstall argocd-gke-dns-endpoint-clusters
