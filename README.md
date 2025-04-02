# Dotfiles

## Installation

Debian / Ubuntu
```
sudo apt install stow
```

Arch
```
sudo pacman -S stow
```

- Clone the repo
- `cd` into it
- use 

```
stow {category} -t ~
```
where `{category}` is one of the root directories of this repo

### Oh My ZSH

Install the p10k theme/plugin 

```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git "${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k"
```

## TO-DO

- [ ] Cleanup and split the nvim into modules
- [ ] Add more of the helper scripts 
- [ ] Combine the aliases and utility functions into the zsh module
- [ ] Cleanup and organize the i3 config
