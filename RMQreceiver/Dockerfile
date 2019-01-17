FROM fabric8/java-alpine-openjdk8-jre
COPY Recv.class /
ENV CLASSPATH amqp-client-5.5.1.jar:slf4j-api-1.7.25.jar:slf4j-simple-1.7.25.jar
CMD ["java", "Recv"]
