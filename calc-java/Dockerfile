FROM openjdk:17-jdk-slim

WORKDIR /DockerfilesPrac

COPY calc.java /DockerfilesPrac

RUN javac calc.java

CMD ["java", "calc.java"]