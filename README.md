# ZSH completion for npm

Clone the repository

```sh
git clone git@github.com:Ajnasz/zsh-npm-completion.git /path/to/somewhere/zsh-npm-completion
```

Add it to `fpath` in you `.zshrc` so it will be loaded when needed

```zsh
fpath=(/path/to/somewhere/zsh-npm-completion $fpath)
```

## oh-my-zsh

If you use oh-my-zsh you must disable the npm plugin as it conflicts with the completion functions of this plugin.
