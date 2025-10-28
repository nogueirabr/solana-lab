# Commads

## POWER SHELL

To list env. variables
```CMD
Get-ChildItem Env: | Format-Table -Wrap -AutoSize
```


## GIT

+ Config

To list the config settings
```git 
 git config --global --list
```

List the settings in the user git config file "--global"
```
cat ~/.gitconfig
```

+ Branchs

To update the local list of remote branches:
```
git remote update origin --prune
```


+ Alias

```
git config --global alias.l5 "git l -5"
```


[alias]
 s = !git status -s
 c = !git add --all && git commit -m
 l = !git log --pretty=format:'%C(magenta)%h%C(green)%d (%C(bold)%cr)%Creset - %s%C(bold italic blue), %cn%Creset'
        co = checkout
        bal = branch -al
        l5 = git l -5
##Ref
* https://www.eficode.com/blog/10-levels-of-git-aliases-beginner-to-intermediate-concepts
* 
