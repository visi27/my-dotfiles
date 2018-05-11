# my-dotfiles

### z Command

* Copy z.sh to ~/z.sh

### Install and config thefuck

* Install from apt

  `sudo apt install thefuck`

* Add this to ~/.zshrc (or ~/.bashrc)

  `eval $(thefuck --alias)`

### Installing zsh-syntax-highlighting

* Clone repository in oh-my-zsh's plugins directory:

  `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting`

* Activate the plugin in ~/.zshrc:

  `plugins=( [plugins...] zsh-syntax-highlighting)`

* Source ~/.zshrc to take changes into account:

  `source ~/.zshrc`
