FROM eclipse-temurin:17
WORKDIR /usr/src/images
COPY . .
COPY ./aws /usr/src/images/aws

EXPOSE 8091

# ENV AWS_CONTAINER_CREDENTIALS_FULL_URI="/home/node/aws"


# RUN ["java", "--version"]

CMD ["java", "-jar", "./imagess3-0.0.1-SNAPSHOT.jar"]

# CMD ["cat", "/etc/hosts"]