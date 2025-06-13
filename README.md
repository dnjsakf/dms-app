### Git Submodules Initialize
```shell
# Remove Cashed
git rm --cached server
git rm --cached client

# Add Submodules
git submodule add https://github.com/dnjsakf/dms-server.git server
git submodule add https://github.com/dnjsakf/dms-client.git client

# Upadte Submodules
git submodule init
git submodule update

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

### Git Submodules Push
```shell
git submodule foreach git add .
git submodule foreach git commit -m "Message"
git submoudle foreach git push origin
```

### Install Lerna
