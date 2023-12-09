# Orbservability Charts

Official Helm charts for Orbservability.

- [Orbservability Observer](./charts/observer) (orbservability/observer)

## Usage

Add via traditional [chart repository](https://helm.sh/docs/topics/chart_repository/):

```shell
helm repo add orbservability https://helm.orbservability.com
helm repo update
```

Add via [OCI-based registry](https://helm.sh/docs/topics/registries/):

```shell
helm registry login ghcr.io --username $GITHUB_ACTOR --password-stdin
```
