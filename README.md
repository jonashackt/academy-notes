# academy-notes
Prerequisites, links, notes for the heise Academy course on GitHub Actions

# 01.02. (Prerequisites)

### git & IDE

I assume you have git & your favorite IDE installed - otherwise do so now. For the course I installed git via my systems package manager (e.g. https://brew.sh/, https://chocolatey.org/ etc.) and IntelliJ as IDE (https://www.jetbrains.com/de-de/idea/download/).

### Install SDKMan

To avoid any trouble with JDK and Maven installations let's use a package manager like https://sdkman.io/install :

```
curl -s "https://get.sdkman.io" | bash
source "$HOME/.sdkman/bin/sdkman-init.sh"
sdk version
```

### Install JDK & Maven

Now simply install a concrete Java version with:

```
sdk install java 17.0.0-tem
java -version
```

And don't forget to install Maven:

```
sdk install maven
mvn --version
```






# 01.03.

### Spring Boot Initializer

https://start.spring.io/


### GitHub Actions Workflow Overview

https://docs.github.com/en/actions/learn-github-actions/introduction-to-github-actions