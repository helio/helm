# Helm

This is a super simple repository for some helm charts we may or may not use. 

## Usage

TL;DR:

```
# create package of folder <name>
$ helm package <name>

# move archive to proper location
$ mv <name>-0.0.1-tgz ../helm  && cd ../helm

# update repo index
$ helm repo index . --url https://helio.github.io/helm/

# then add, commit & push the changes using git
```

Full version: https://medium.com/containerum/how-to-make-and-share-your-own-helm-package-50ae40f6c221
