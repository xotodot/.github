- 🌱 @xotodot : dot files


<hr>

#### clone dotfles 

```bash
# make backup of your git config
mv .config .config-bk
# clone config sub repositories
git clone --recurse-submodules https://github.com/xotodot/xotodot.git > /dev/null ~/.config
```

#### clone full repo

1. get your token from [notion](https://www.notion.so/xotosphere/5403dfd3c8d145088eae43b66e074087?v=5c015ea5f572455681c6be323401e580)
2. apply your token and run simple command to clone 👇🏽

```bash 
wget -qO- https://raw.githubusercontent.com/xotoscript/xotoscript-git-orgclone/development/install.sh | bash -s -- --token ghp_xxx --username xotosphere --clean false --organization xotodot
```


