# helm-charts
Private helm chart repository

To add repository to local helm repository list:
```sh
helm repo add komatooo \
  --username "${GITHUB_TOKEN}" \
  --password "${GITHUB_TOKEN}" \
  "https://raw.githubusercontent.com/komatooo/helm-charts/master/"
```
Then update charts index:
```
helm repo update
```

To find chart in repo:
```
helm search repo chart --devel
```
