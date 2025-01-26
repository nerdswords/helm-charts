> ⚠️ **DEPRECATION NOTICE** ⚠️
> YACE is now part of [prometheus-community](https://github.com/prometheus-community/yet-another-cloudwatch-exporter), the helm chart for new YACE releases has been moved the prometheus-community [helm-charts repo](https://github.com/prometheus-community/helm-charts/tree/main/charts/prometheus-yet-another-cloudwatch-exporter).

# Helm chart for Yace

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

Helm chart for [YACE](https://github.com/nerdswords/yet-another-cloudwatch-exporter).

## Usage

[Helm](https://helm.sh) must be installed to use the chart.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo and install the chart as follows:

```sh
helm repo add nerdswords https://nerdswords.github.io/helm-charts
helm install nerdswords/yet-another-cloudwatch-exporter
```

Chart documentation is available in [chart directory](charts/yet-another-cloudwatch-exporter/README.md).
