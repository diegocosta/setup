# vscode 

### Install Extensions
Open a terminal, change to directory where you cloned this repo, and type:

**... on UNIX-Like OS:**
```sh
for i in $(cat extensions); do code --install-extension $i; done
```

**... on Windows:**
```sh
for /F %i in ('type extensions') do code --install-extension %i 
```
