# Terminal Shortcut

- Use for store configuration of `~/.bash_profile`, `~/.bashrc`, or `~/.zshrc`
- Activate by `source <Configuration File>` 
- Ex: `source ~/.zshrc`

## Normal Usage

```
alias dt="cd ~/Desktop"
alias pv="cd .."
alias c="code ."
alias -s {js,ts,html,css,md,json,py,yml,yaml,dart,rb}=code
alias config="vi ~/.zshrc"
alias act="source ~/.zshrc"
```

## Git Shortcut

```
alias gi="git init"
alias ga="git add"
alias gaa="git add ."
alias gc="git clone"
alias gcm="git commit -m"
alias gph="git push"
alias gpho="git push -u"
alias gpl="git pull"
alias gs="git status"
alias grm="git remote add origin"
```

## Docker

```
alias d="docker"
alias dps="docker ps"
alias dcu="docker-compose up"
alias dc="docker-compose"
```

## Flutter
```
alias fpg="flutter pub get"
alias fc="flutter create"
```

## Compilation
```
alias py="python3"
alias n="node"
alias rb="ruby"
```

## Open Link
```
alias gh="obs https://github.com/ggolfz $1"
alias ggolfz="obs https://ggolfz.codes"
obs() {
    if [ x"$2" = x"init" ] ; then obs https://github.com/new ;  
    else open $1/$2 -a /Applications/Microsoft\ Edge.app ;
    fi
}

```
