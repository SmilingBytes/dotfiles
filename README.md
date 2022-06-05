# Try Out My Dot Files


**IMPORTANT:** Make sure to remove or move your current dot files and/or directory.




## How To Use (Full Configurations):
1. [Install NeoVim](https://github.com/neovim/neovim/wiki/Installing-Neovim)
2. Setup [NvChad](https://nvchad.github.io) 
3. Take a backup
4. Run Following Terminal Commands: 
 
**Please take a backup following files/directory:**

- [ ] ~/.gitignore
- [ ] ~/.gitignore_global
- [ ] ~/.bashrc
- [ ] ~/.bash_aliases
- [ ] ~/.zshrc
- [ ] ~/.config/nvim/lua/custom
- [ ] ~/.pre-commit-config.yaml
- [ ] ~/.flake8


**Terminal Commands**

```sh
cd ~
git init 
git remote add origin https://github.com/ismail-h-rana/dotfiles.git 
git pull origin master 
nvim +PackerSync
```

## License

MIT

**Free Software, Hell Yeah!**
