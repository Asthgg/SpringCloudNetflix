FROM openjdk:17.0.2-jdk-oracle
VOLUME /tmp
EXPOSE 9093
COPY target/bank-transaction-0.0.1.jar /bank-transaction-0.0.1.jar
ENTRYPOINT [ "java","-jar","bank-transaction-0.0.1.jar" ]