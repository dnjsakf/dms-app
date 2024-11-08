### Git Submodules Initialize
```shell
# Remove Cashed
git rm --cached batch
git rm --cached server
git rm --cached client

# Add Submodules
git submodule add https://dnjsakf.synology.me:18443/dnjsakf/dms-batch.git batch
git submodule add https://dnjsakf.synology.me:18443/dnjsakf/dms-server.git server
git submodule add https://dnjsakf.synology.me:18443/dnjsakf/dms-client.git client

# Upadte Submodules
git submodule init
git submodule update

git add .gitmodules batch
git add .gitmodules server
git add .gitmodules client
```

### Git Submodules Clone
```shell
# Main Product Clone 후
git submodule init
git submodule update
git submoudle foreach git checkout dev
```

### Install Lerna
