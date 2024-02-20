# 🌱 @xotodot : dot files

#### ➡️ A. clone dotfles 
```bash
# make backup of your git config
mv ~/.config ~/.config-bk
# clone config sub repositories
git clone --recurse-submodules git@github.com:xotodot/xotodot.git > /dev/null ~/.config
```

#### ➡️ B. clone full organization

1. get your token
2. apply your token and run simple command to clone 👇🏽
```bash
# clone all repositories in organization in one folder
wget -qO- https://raw.githubusercontent.com/xotoscript/xotoscript-git-orgclone/development/install.sh | bash -s -- --token ghp_xxx --username xotosphere --clean false --organization xotodot
```


