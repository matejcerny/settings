# Development
```
mkdir ~/dev/git -p
brew install git
brew cask install intellij-idea
brew tap AdoptOpenJDK/openjdk
brew cask install adoptopenjdk8
brew cask install adoptopenjdk11
brew install jenv
brew cask install docker
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