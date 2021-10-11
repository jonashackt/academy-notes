# academy-notes
Prerequisites, links, notes for the heise Academy course on GitHub Actions

# Prerequisites

#### Install git

I assume you have git installed - otherwise:

```
# Mac (https://brew.sh/):
brew install git

# Windows (https://chocolatey.org/install):
choco install git
```

#### Install SDKMan

To avoid any trouble with JDK and Maven installations let's use a package manager like https://sdkman.io/install :

```
curl -s "https://get.sdkman.io" | bash
source "$HOME/.sdkman/bin/sdkman-init.sh"
sdk version
```

#### Install JDK & Maven

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


#### Spring Boot Initializer

https://start.spring.io/



# 01.03.

### GitHub Actions Workflow Overview

https://docs.github.com/en/actions/learn-github-actions/introduction-to-github-actions