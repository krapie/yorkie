# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/krapie/yorkie.git
# cd into the cloned directory
git checkout f74fe111b980575786fe2d900806d950ec6c1512
helm template . --name-template yorkie-app --include-crds
```
