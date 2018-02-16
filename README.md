

## Required setup

TODO: Is it easier to just Ansible-ize all of this setup?

* Git
  * macOS: Just type `git` to invoke the Command Line Tools installer for your OS version
  * Ubuntu: Run `apt-get install -y git`
* Homebrew (macOS only) - need link to setup script
* ZSH
  * Installed on macOS by default
  * Ubuntu: run `apt-get install -y zsh`
* `oh-my-zsh` - need link to setup script
* tmux
  * macOS: `brew install tmux`
  * Ubuntu: `apt-get install -y tmux`
* Vim
  * Command line `vim` should already be installed on both macOS and Ubuntu
  * macOS: Get MacVim (optional)
* Ruby
  * macOS: `brew install ruby` or get rbenv
  * Ubuntu: Either set up rbenv, or get [ruby-build](https://github.com/rbenv/ruby-build) and use it to set up a preferred Ruby in e.g. `/usr/local/ruby`. (I like to create `/usr/local/ruby/versions/$VERSION` and symlink its `bin` directory into `/usr/local/ruby/bin`)
* [Visual Studio Code](http://code.visualstudio.com/)
* A terminal application (iTerm, [Hyper](https://hyper.is), or macOS Terminal.app)