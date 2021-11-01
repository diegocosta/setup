# vscode 
<img width="1291" alt="Screen Shot 2021-11-01 at 13 16 10" src="https://user-images.githubusercontent.com/3134422/139704369-16dfab28-138e-47d6-9abf-2fc505f310a0.png">

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
