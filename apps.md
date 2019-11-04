# MacOS applications
## Package manager
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew update
```

## Terminal
```
brew cask install iterm2
brew install bash
sudo cp configs/shells /etc/shells
chsh -s /usr/local/bin/bash $USER # this will set for the current user.

brew install grc
cp configs/.bash_profile ~/.bash_profile

ssh-add -K ~/.ssh/cerny_private_pass.pem
cp configs/config ~/.ssh/config
```

## Development
```
mkdir ~/dev/git -p
brew install git
brew cask install intellij-idea
brew cask install homebrew/cask-versions/adoptopenjdk8
brew install apache-spark
brew cask install anaconda2
brew cask install virtualbox
brew install docker docker-machine
brew cask install docker-toolbox
docker-machine create --driver virtualbox default
```

## BigData
```
brew install --HEAD coursier/formulas/coursier
```
https://almond.sh/docs/quick-start-install

## Nexus certificate
```
sudo keytool -importcert -file cert.cer -keystore /Library/Java/JavaVirtualMachines/adoptopenjdk-8.jdk/Contents/Home/jre/lib/security/cacerts
```

## Remapping of home/end keys
```
mkdir ~/Library/KeyBindings/
cp configs/DefaultKeyBinding.dict ~/Library/KeyBindings/
```

## Utils & other
```
brew install micro
brew cask install opera
brew cask install atom
brew cask install google-backup-and-sync
brew cask install balenaetcher
brew cask install evernote
brew cask install vlc
brew install wine
```
