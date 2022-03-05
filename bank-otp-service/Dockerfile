FROM openjdk:17.0.2-jdk-oracle
VOLUME /tmp
EXPOSE 9094
COPY target/bank-otp-0.0.1.jar /bank-otp-0.0.1.jar
ENTRYPOINT [ "java","-jar","bank-otp-0.0.1.jar" ]