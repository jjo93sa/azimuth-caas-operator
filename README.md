## Usage

[Helm](https://helm.sh) must be installed to use the charts. Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

helm repo add azimuth-caas-operator https://jjo93sa.github.io/azimuth-caas-operator

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages. You can then run `helm search repo
azimuth-caas-operator` to see the charts.

To install the azimuth-caas-operator chart:

    helm install azimuth-caas-operator azimuth-caas-operator/azimuth-caas-operator

To uninstall the chart:

    helm delete azimuth-caas-operator
