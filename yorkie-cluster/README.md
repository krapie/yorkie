# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/krapie/yorkie.git
# cd into the cloned directory
git checkout 2a3a1578a0ee3dbb8ed0a2f5668fed5b98513ffc
helm template . --name-template yorkie-app --include-crds
```
