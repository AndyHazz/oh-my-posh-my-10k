# oh-my-posh My 10k theme

Theme file for oh my posh, based on powerlevel 10k rainbow

![oh-my-posh my 10k example](https://raw.githubusercontent.com/andyhazz/oh-my-posh-my-10k/main/my-10k.png)


URL for including theme:

```
https://andyhazz.github.io/oh-my-posh-my-10k/my-10k.omp.json
```

Add to the end of ~/.zshrc:

```
eval "$(oh-my-posh init zsh --config https://andyhazz.github.io/oh-my-posh-my-10k/my-10k.omp.json)"
```

From scratch:

```
# install zsh via package manager, e.g:
sudo apt install zsh

# make zsh your default shell
chsh -s $(which zsh)

# install oh my posh
curl -s https://ohmyposh.dev/install.sh | bash -s

# add required lines to end of .zshrc config
echo 'export PATH=$PATH:~/.local/bin' >> ~/.zshrc
echo 'eval "$(oh-my-posh init zsh --config https://andyhazz.github.io/oh-my-posh-my-10k/my-10k.omp.json)"' >> ~/.zshrc

# restart zsh
zsh
```