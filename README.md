# configs

## CLI
Download `.zshrc`, `.aliases.zsh` & `.p10k.zhs` and other files from this repo.

Follow more specific instructons ⬇️

### ZSH
1. `sudo apt install zsh `
2. Install [ohmyzsh](https://github.com/ohmyzsh/ohmyzsh)
3. Install plugins
- [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md)
- [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md)
4. Install [p10k](https://github.com/romkatv/powerlevel10k?tab=readme-ov-file#getting-started)
5. Install [Mise-en-place](https://mise.jdx.dev/getting-started.html)


#### CLI based tools
- [Zoxide](https://github.com/ajeetdsouza/zoxide)
- [ripgrep](https://github.com/BurntSushi/ripgrep)
- [fd](https://github.com/sharkdp/fd)
  - `mise use -g fd@latest`
- [eza](https://github.com/eza-community/eza/blob/main/INSTALL.md)
  - install completions to `~/.config/eza/completions/zsh`, if needed
  - `mv ./.aliases.zsh $ZSH_CUSTOM/.aliases.zsh`

### [Zellij](https://zellij.dev/documentation/)
1. On Ubuntu download or build the binary: https://github.com/zellij-org/zellij/releases
2. Move binary to `/usr/local/bin`
3. Run `chmod +x zellij`
4. Update terminal of choice to start with `zellij` or `zellij -l welcome`


### Other plugins
- [Lazygit](https://github.com/jesseduffield/lazygit)
- [Difftastic](https://difftastic.wilfred.me.uk/installation.html)
- [Lazydocker](https://github.com/jesseduffield/lazydocker)
