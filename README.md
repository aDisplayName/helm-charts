helm-charts
=

To connect the repo:
```
helm repo add adisplayname https://adisplayName.github.io/helm-charts/charts
```

# Code Structure
The helm chart packages are served under the [Releases](https://github.com/aDisplayName/helm-charts/releases).

The helm chart [`index.yaml`](https://github.com/aDisplayName/helm-charts/blob/gh-pages/charts/index.yaml) are served under the [`charts`](https://github.com/aDisplayName/helm-charts/tree/gh-pages/charts) folder at [`gh-pages`](https://github.com/aDisplayName/helm-charts/tree/gh-pages) branch.

The GitHub Pages is then set-up by serving the root folder of [`gh-pages`](https://github.com/aDisplayName/helm-charts/tree/gh-pages) branch at `https://adisplayName.github.io/helm-charts`.
