# Development
```
mkdir ~/dev/git -p
brew install ansible

brew tap AdoptOpenJDK/openjdk
brew install adoptopenjdk8
brew install adoptopenjdk11

brew install awscli
brew install docker
brew install git
brew install intellij-idea
brew install jenv
brew install kubernetes-cli
brew install pgadmin4
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
