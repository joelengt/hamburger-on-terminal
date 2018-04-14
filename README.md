# Hamburger-on-terminal
A nice hamburger on my terminal

![alt text](https://github.com/joelengt/hamburger-on-terminal/blob/master/29751176_1799264796792617_63374563_n.png?raw=true)

## Install Oh-My ZSH Terminal
Follow the rules https://github.com/robbyrussell/oh-my-zsh

## Be sure to know what and where is your current theme.
* If your want to know your current theme, take a look in ~/.zshrc

```
  ...
  ZSH_THEME="maran"
  ...
```

## Edit the template with vim, nano, etc.
* Edit your terminal theme. In this example is robbyrussell.zsh-theme

```sh
cd ~
ls -a
cd .oh-my-zsh
cd /themes
vim robbyrussell.zsh-theme
```

## Customize your terminal
If you really want a emoji on your terminal, just copy and paste it.

```sh
local ret_status="%(?:%{$fg_bold[green]%}🍒 :%{$fg_bold[red]%}🍒 )"
PROMPT='${ret_status} %n@%m:%{$fg[cyan]%}%c%{$reset_color%} $(git_prompt_info)'

ZSH_THEME_GIT_PROMPT_PREFIX="%{$fg_bold[blue]%}git:(%{$fg[red]%}"
ZSH_THEME_GIT_PROMPT_SUFFIX="%{$reset_color%} "
ZSH_THEME_GIT_PROMPT_DIRTY="%{$fg[blue]%}) %{$fg[yellow]%}✗"
ZSH_THEME_GIT_PROMPT_CLEAN="%{$fg[blue]%})"
```

* save and restart your terminal

Done!

## More emojis

🍒
🍜
🍥
🍧
🍰
🍺


source
http://apps.timwhitlock.info/emoji/tables/unicode

