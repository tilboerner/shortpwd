# shortpwd

Print a shortened version of the current working directory to stdout. Use in console prompt:

```
~$ cd Downloads/screeps-typescript-starter-master/src/components/creeps/roles/
~/Dow…/scr…/src/com…/cre…/roles$
```

For use with bash, you can include it in your prompt like this:

```
export PS1='$(~/bin/shortpwd)\$ '
```
