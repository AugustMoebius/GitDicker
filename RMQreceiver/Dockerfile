FROM fabric8/java-alpine-openjdk8-jre
COPY Recv.class /
ENV CLASSPATH .amqp-client-5.5.1.jar
CMD ["java", "Recv"]
