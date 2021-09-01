# Learning Zsh

Just one of the things I'm learning. <https://github.com/hchiam/learning>

Slightly better [`bash`](https://github.com/hchiam/learning-bash-scripts), and apparently [`bash` commands are mostly compatible with `zsh`](https://medium.com/@harrison.miller13_28580/bash-vs-z-shell-a-tale-of-two-command-line-shells-c65bb66e4658), although [there are differences in interactive use, scripting (like indices), and some nice `zsh` features](https://apple.stackexchange.com/questions/361870/what-are-the-practical-differences-between-bash-and-zsh).

Switching from bash to zsh on Mac:

https://support.apple.com/en-us/HT208050

```bash
`chsh -s /bin/zsh`
```

(If you need to go back to defaulting to bash, then run `chsh -s /bin/bash`)

`~/.zshenv` is zsh's version of bash's `~/.bash_profile`:

https://stackoverflow.com/a/60982415

```bash
echo source ~/.bash_profile > ~/.zshenv && source ~/.zshenv
```

Setting up zsh to use fish autosuggestion + syntax highlighting:

https://github.com/zellwk/dotfiles/blob/master/install-zsh.sh

5 startup files that zsh reads commands from:

http://zsh.sourceforge.net/Intro/intro_3.html

```
$ZDOTDIR/.zshenv
$ZDOTDIR/.zprofile
$ZDOTDIR/.zshrc
$ZDOTDIR/.zlogin
$ZDOTDIR/.zlogout
```

The difference between bash, zsh, and fish, and also which to use:

https://zellwk.com/blog/bash-zsh-fish

Mac switched from bash to zsh:

https://www.theverge.com/2019/6/4/18651872/apple-macos-catalina-zsh-bash-shell-replacement-features
