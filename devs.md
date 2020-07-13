# Development
```
mkdir ~/dev/git -p
brew install git
brew cask install intellij-idea
brew cask install homebrew/cask-versions/adoptopenjdk8
```

## Docker
```
https://download.docker.com/mac/stable/Docker.dmg
```

## BigData
```
brew install apache-spark
brew cask install anaconda2
```

Scala kernel for Jupyter https://almond.sh/docs/quick-start-install
```
brew install --HEAD coursier/formulas/coursier
```

## Nexus certificate
```
sudo keytool -importcert -file cert.cer -keystore /Library/Java/JavaVirtualMachines/adoptopenjdk-8.jdk/Contents/Home/jre/lib/security/cacerts
```