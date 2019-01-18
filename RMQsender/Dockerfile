FROM fabric8/java-alpine-openjdk8-jre
COPY Send.class /
COPY amqp-client-5.5.1.jar /
COPY slf4j-api-1.7.25.jar / 
COPY slf4j-simple-1.7.25.jar /
CMD java -cp .:amqp-client-5.5.1.jar:slf4j-api-1.7.25.jar:slf4j-simple-1.7.25.jar Send
