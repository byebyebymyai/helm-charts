# helm-charts

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add byebyebymyai https://byebyebymyai.github.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo byebyebymyai` to see the charts.

To install the `v2ray` chart:

    helm install v2ray byebyebymyai/v2ray

To uninstall the chart:

    helm delete v2ray