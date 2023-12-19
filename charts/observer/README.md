# Observer Helm Chart

<!-- ![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/orbservability/observer?label=latest) -->

<https://github.com/orbservability/observer>

## Usage

Install via traditional [chart repository](https://helm.sh/docs/topics/chart_repository/):

```shell
helm repo add orbservability https://orbservability.github.io/helm-charts/
helm repo update
helm install observer orbservability/observer
```

Install via [OCI-based registry](https://helm.sh/docs/topics/registries/):

```shell
helm registry login ghcr.io --username $GITHUB_ACTOR --password-stdin
helm pull oci://ghcr.io/orbservability/charts/observer
helm install observer observer-[tag].tgz
```
