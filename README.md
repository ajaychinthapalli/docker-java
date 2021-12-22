# docker-java

```text
1. git clone https://github.com/ajaychinthapalli/docker-java.git
2. cd docker-java
3. mvn package
4. java -jar target/find-links.jar https://google.com
//dockerize
// create a docker image
5. docker build -t docker-java:1.0 .
// run it
6. docker run -t docker-java:1.0 https://google.com
# client
# tag
7. docker image tag docker-java:1.0 achin16/docker-java:1.0
# push
8. docker image push achin16/docker-java:1.0
# server
9. docker pull achin16/docker-java:1.0
```

