# Applications
## Package manager
```
xcode-select --install
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew update
```

## Terminal
```
brew install iterm2

ssh-add -K ~/.ssh/cerny_private_pass.pem
cp configs/config ~/.ssh/config
```
### OhMyZSH
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k

brew tap homebrew/cask-fonts
brew install font-fira-code

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
brew install atom
brew install balenaetcher
brew install brave-browser
brew install boostnote
brew install cyberduck
brew install google-backup-and-sync
brew install keka
brew install signal
brew install transmission
brew install vlc
```
