# Try Out My Dot Files


**IMPORTANT:** Make sure to remove or move your current dot files and/or directory.

## Install
1. Take a backup
  ```sh
  mkdir ~/backup_dotfiles
  mv ~/.gitignore ~/backup_dotfiles/.gitignore
  mv ~/.gitignore_global ~/backup_dotfiles/.gitignore_global
  mv ~/.bashrc ~/backup_dotfiles/.bashrc
  mv ~/.bash_aliases ~/backup_dotfiles/.bash_aliases
  mv ~/.zshrc ~/backup_dotfiles/.zshrc
  mv ~/.pre-commit-config.yaml ~/backup_dotfiles/.pre-commit-config.yaml
  mv ~/.flake8 ~/backup_dotfiles/.flake8
  ```
  
2. Install Dot Files
 ```sh
 cd ~
 git init
 git remote add origin https://github.com/ismail-h-rana/dot-files.git
 git pull origin master
 source ~./bashrc
 ```
 If you use **zsh:** `exec zsh`

## Uninstall & Restore Previous Setup

```sh
cd ~
rm -rf .gitignore .gitignore_global .bashrc .bash_aliases .zshrc .pre-commit-config.yaml .flake8
mv ~/backup_dotfiles/.gitignore ~/.gitignore
mv ~/backup_dotfiles/.gitignore_global ~/.gitignore_global
mv ~/backup_dotfiles/.bashrc ~/.bashrc
mv ~/backup_dotfiles/.bash_aliases ~/.bash_aliases
mv ~/backup_dotfiles/.zshrc ~/.zshrc
mv ~/backup_dotfiles/.pre-commit-config.yaml ~/.pre-commit-config.yaml
mv ~/backup_dotfiles/.flake8 ~/.flake8
source ~/.bashrc
```
If you use **zsh**: `exec zsh`


## License

MIT

**Free Software, Hell Yeah!**
