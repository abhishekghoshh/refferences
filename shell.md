
### Download and set zsh
```
sudo apt-get install zsh
chsh -s $(which zsh)
echo $SHELL
sudo chsh -s $(which zsh) $USER
```

### Download and install material theme zsh
```
curl -L -o ~/.oh-my-zsh/custom/themes/materialshell.zsh-theme https://raw.githubusercontent.com/carloscuesta/materialshell/master/materialshell.zsh
ZSH_THEME="materialshell"
source ~/.zshrc

```