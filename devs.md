# Development

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

### Apps
```
mkdir -p ~/dev/backup
mkdir -p ~/dev/git
mkdir -p ~/dev/temp

brew install ansible
brew install awscli
brew install azure-cli
brew install --cask docker
brew install git
brew install intellij-idea
brew install jenv
brew install kubernetes-cli
brew install lens
brew install pgadmin4
brew install postman
brew install robo-3t
brew install --cask temurin17
brew install terraform
brew install terraforming
```

## BigData
```
brew install apache-spark
brew install anaconda2
```

Scala kernel for Jupyter https://almond.sh/docs/quick-start-install
```
brew install --HEAD coursier/formulas/coursier
```

## Nexus certificate
```
sudo keytool -importcert -file cert.cer -keystore /Library/Java/JavaVirtualMachines/adoptopenjdk-8.jdk/Contents/Home/jre/lib/security/cacerts
```
