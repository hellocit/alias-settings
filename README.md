# alias-settings
## my life (そういえばgithubのどこかにもとにした.zshrcがあるはず...)

### I will add alias
`alias .1='..'`
`alias .2='../..'`
`alias .3='../../..'`
`alias .4='../../../..'`


### let`s note zsh for wsl alias
`alias -g L='| less'`
`alias -g H='| head'`
`alias -g G='| grep'`
`alias -g GI='| grep -ri'`
`alias lst='ls -ltr --color=auto'`
`alias l='ls -ltr --color=auto'`
`alias la='ls -la --color=auto'`
`alias ll='ls -l --color=auto'`
`alias so='source'`
`alias v='vim'`
`alias vi='vim'`
`alias vz='vim ~/.zshrc'`
`alias c='cdr'`
`alias h='fc -lt '%F %T' 1'`
`alias cp='cp -i'`
`alias rm='rm -i'`
`alias mkdir='mkdir -p'`
`alias ..='c ../'`
`alias back='pushd'`
`alias diff='diff -U1'`
`alias gitall='git add -A && git commit --allow-empty-message -m "" && git push origin $(git branch | sed -n -e "s/^\* \(.*\)/\1/p")'`
`alias ..='cd ..'`
`alias ...='cd ../..'`
`alias ....='cd ../../..'`
`alias zmv='noglob zmv -W'`
# References
* https://github.com/hellocit/zsh_install
* 
* 
* 
* 
* 