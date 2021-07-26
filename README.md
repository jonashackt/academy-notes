# academy-notes
Prerequisites, links, notes for the heise Academy course on GitHub Actions

## Prerequisites

#### Install JDK & Maven

```
curl -s "https://get.sdkman.io" | bash
source "$HOME/.sdkman/bin/sdkman-init.sh"
sdk version
```

now simply install a concrete Java version with:

```
sdk install java 16.0.1.hs-adpt
java -version
```

don't forget to install Maven:

```
sdk install maven
mvn --version
```


#### Spring Boot Initializer

https://start.spring.io/



# 01.03.

### GitHub Actions Workflow Overview

https://docs.github.com/en/actions/learn-github-actions/introduction-to-github-actions