# zsh-exa-ls-plugin

## Deprecated

Due to exa is unmaintained, we use the fork eza instead of exa. Please use [birdhackor/zsh-eza-ls-plugin](https://github.com/birdhackor/zsh-eza-ls-plugin) instead.

## Old Intro

This zsh plugin enables a number of aliases allowing `exa`, to act as a drop-in
replacement for `ls` and `tree`.

This plugin is inspired by [MohamedElashri/exa-zsh](https://github.com/MohamedElashri/exa-zsh)
and [zpm-zsh/ls](https://github.com/zpm-zsh/ls)

## Installation

### Install exa
Install [`exa`](https://the.exa.website). See
[exa installation](https://the.exa.website/#installation) for platform specific
installation instructions.

### Next (Manually)
Next, download this repo into your custom plugins directory. For my installation
using [Oh My Zsh](https://ohmyz.sh/), Clone the repo to
`~/.oh-my-zsh/custom/plugins`.

Finally, add `zsh-exa-plugin` to the plugins array of your zshrc file:

```sh
plugins=(... zsh-exa-ls-plugin)
```

### Next (zplug)

Add `zplug birdhackor/zsh-exa-ls-plugin` to your `~/.zshrc` and re-open your terminal session.
