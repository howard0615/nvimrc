### Howard's init.lua
This nvim is based on [THePrimeagen's nvim_rc](https://github.com/ThePrimeagen/neovimrc/tree/master)
This is my new RC.  There is no video yet.

### Change Log
[cd1167a](https://github.com/ThePrimeagen/neovimrc/commit/cd1167a72240b2052eb182f2a5f27b29be1ec627)
* added another remap, <leader>tf (leader test file), to run the entire file
  using neotest

### Needed package install

ripgrep
npm
luarocks


### How to install neovim

[install](https://github.com/neovim/neovim/blob/master/INSTALL.md)


### Install environment oh-my-zsh
```
sudo apt install vim curl git
sudo apt install zsh
chsh -s $(which zsh)

# install oh-my-zsh
wget https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh
sh install.sh

# install powerlevel10k
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k

# edit .zshrc and add in
ZSH_THEME="powerlevel10k/powerlevel10k"

# back to terminal
source ~/.zshrc

p10k configure
```
