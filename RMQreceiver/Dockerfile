FROM fabric8/java-alpine-openjdk8-jre
javac -cp amqp-client-5.5.1.jar Recv.java
java -cp .:amqp-client-5.5.1.jar:slf4j-api-1.7.25.jar:slf4j-simple-1.7.25.jar Recv
