---
title: Java
parent: Dev
---

## Windows setup

### Downloads

- [IntelliJ](https://www.jetbrains.com/idea/download/)
- [JetBrains Activator](https://3.jetbra.in/)
- [Gradle](https://gradle.org/releases/)
- [Maven](https://maven.apache.org/download.cgi)
- [Rapid Environment Editor](https://www.rapidee.com/en/download)

## macOS setup

### Brew

#### Install

```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

#### Install formula & cask

```shell
brew install --cask intellij-idea
```

### SDKMAN!

#### Install

```shell
curl -s "https://get.sdkman.io" | bash
```

```shell
source "$HOME/.sdkman/bin/sdkman-init.sh"
```

```shell
sdk version
```

### Java SDK

#### Install

```shell
sdk install java 21.0.3-amzn
```

#### List

```shell
sdk list java
```

#### Set default

```shell
sdk default java 21.0.3-amzn
```

```shell
sdk default java 17.0.12-amzn
```

```shell
sdk default java 8.0.412-amzn
```

#### Check version

```shell
java -version
```

### Maven

#### Install

```shell
sdk install maven
```

#### List

```shell
sdk list maven
```

### Gradle

#### Install

```shell
sdk install gradle
```

#### List

```shell
sdk list gradle
```
