# Helm charts repository

To add repository to local helm repository list:

```sh
helm repo add komatooo https://komatooo.github.io/helm-charts/
```

Then update charts index:

```sh
helm repo update
```

To find chart in repo:

```sh
helm search repo chart --devel
```
