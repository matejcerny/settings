# Applications
## Package manager
```
xcode-select --install
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew update
```

## Terminal
```
brew cask install iterm2

ssh-add -K ~/.ssh/cerny_private_pass.pem
cp configs/config ~/.ssh/config
```
### OhMyZSH
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k

download & install https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/FiraCode

git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
cp configs/.zshrc ~/.zshrc

```
### Bash (optional)
```
brew install bash
sudo cp configs/shells /etc/shells
chsh -s /usr/local/bin/bash $USER # this will set for the current user.

brew install grc
cp configs/.bash_profile ~/.bash_profile
```

## Productivity
```
https://affinity.serif.com/en-gb/designer/
https://www.blackmagicdesign.com/products/davinciresolve/
https://community.gopro.com/t5/en/GoPro-legacy-software/ta-p/595533
```

## Other
```
brew cask install atom
brew cask install balenaetcher
brew cask install brave-browser
brew cask install cyberduck
brew cask install evernote
brew cask install google-backup-and-sync
brew cask install keka
brew cask install signal
brew cask install transmission
brew cask install vlc
```
