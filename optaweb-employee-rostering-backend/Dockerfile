FROM adoptopenjdk/openjdk11:x86_64-ubi-minimal-jre-11.0.13_8
COPY target/quarkus-app /opt/app
WORKDIR /opt/app
CMD ["java", "-jar", "quarkus-run.jar"]
EXPOSE 8080
