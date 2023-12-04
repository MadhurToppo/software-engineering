# Java Software Development Commands

## Create a Spring Boot Project from scratch using Curl command

```shell
mkdir user-service && \
curl https://start.spring.io/starter.tgz \
-d 'type=gradle-project' \
-d 'language=java' \
-d 'bootVersion=3.1.0' \
-d 'groupId=com.madhurtoppo' \
-d 'artifactId=user-service' \
-d 'name=user-service' \
-d 'description=Spring boot application for User Service' \
-d 'packageName=com.madhurtoppo.userservice' \
-d 'packaging=jar' \
-d 'javaVersion=17' \
-d 'dependencies=web' | \
tar -xzvf - --directory user-service/
```

## Spring Boot starter help

```sh
curl https://start.spring.io
```

## Gradle Refresh Dependencies Build

```sh
gradle --refresh-dependencies build
```

### Compile java files from 'src' directory

```sh
cd src
javac -d classes -cp . modern/challenge/*.java
```

### Run Java file containing the Main method

```sh
java -cp classes/ modern/challenge/Main
```
