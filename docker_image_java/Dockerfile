FROM adoptopenjdk:11
WORKDIR /var/dockerjava
COPY helloworld.java .
RUN javac helloworld.java
EXPOSE 8080
CMD ["java", "helloworld"]
