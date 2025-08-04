# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/krapie/yorkie.git
# cd into the cloned directory
git checkout 51882c1d3b613378043e9791631799fc6ba36160
helm template . --name-template yorkie-app --include-crds
```
