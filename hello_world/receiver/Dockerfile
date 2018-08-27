FROM openjdk:10

COPY build/libs/ /usr/app

WORKDIR /usr/app
CMD ["java", "-jar", "rabbitmq_tutorial__hello_world__receiver-0.0.1-SNAPSHOT.jar"]