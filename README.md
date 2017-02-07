# MyBash
MyBash is set of simple bash aliases and functions

# how to use
```bash
if [ -f ~/MyBash/.gitfunctions ]; then
    . ~/MyBash/.gitfunctions
fi

export PS1="\[\e[37m\]\u\[\e[m\]@\h \[\e[33m\]\w\[\e[m\] \$(parse_git_branch)\033[0;33m\$ \033[0m"

if [ -f ~/MyBash/.alias ]; then
    . ~/MyBash/.alias
fi
```
