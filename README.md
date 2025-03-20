# SpechtLabs Helm Charts

[![Release Charts](https://github.com/specht-labs/helm-charts/actions/workflows/release.yaml/badge.svg)](https://github.com/specht-labs/helm-charts/actions/workflows/release.yaml)

📦 A collection of **Helm charts** used at SpechtLabs to simplify and standardize Kubernetes deployments.

## 🚀 Available Charts

| Chart Name       | Description                                                                                | Version  |
|------------------|--------------------------------------------------------------------------------------------|----------|
| hugo-hoster      | A Helm chart for hosting hugo blogs in Kubernetes with S3 to serve the static content.     | `0.0.6`  |
| urlshortener     | A Helm chart for urlshortener, a Kubernetes native URL Shortening and redirection service. | `0.0.14` |

## 📥 Installation

To use a Helm chart from this repository, add the SpechtLabs Helm repository:

```bash
helm repo add spechtlabs https://spechtlabs.github.io/helm-charts
helm repo update
```
