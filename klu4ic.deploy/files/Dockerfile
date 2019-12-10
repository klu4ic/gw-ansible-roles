FROM openjdk:8-jre-alpine 
ADD http://54.214.218.55:8081/service/rest/v1/search/assets/download?sort=version&repository=maven-releases&maven.groupId=spring-boot-artifact&maven.artifactId=spring-boot-smoke-test-web-ui-2.2.1&maven.extension=jar /web-ui.jar
EXPOSE 8080
ENTRYPOINT ["/usr/bin/java", "-jar", "/web-ui.jar", "--server.port=8080"]
