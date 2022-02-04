# AWS-Vault ZSH Plugin
## DEPRECATED This plugin is not maintained anymore. Use https://github.com/blimmer/zsh-aws-vault instead. The completion script has been contributed to that repo so you get the exact same thing.



[![asciicast](https://asciinema.org/a/266736.svg)](https://asciinema.org/a/266736)

## Installation

### [Antigen](https://github.com/zsh-users/antigen)

```
antigen bundle reegnz/aws-vault-zsh-plugin
```

### [Zgen](https://github.com/tarjoilija/zgen)

```
zgen load reegnz/aws-vault-zsh-plugin
```

### [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)


1. Clone this repository into oh-my-zsh's plugins directory:
```
git clone https://github.com/reegnz/aws-vault-zsh-plugin.git \
  ~/.oh-my-zsh/custom/plugins/aws-vault-zsh-plugin
```

2. Activate the plugin in `~/.zshrc`:

```
plugins=( [plugins...] aws-vault-zsh-plugin)
```
