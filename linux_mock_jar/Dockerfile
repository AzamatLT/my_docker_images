FROM bellsoft/liberica-openjdk-alpine-musl
EXPOSE 9000
COPY ./mock.jar .
COPY ./properties.yaml .
CMD ["java","-jar","mock.jar"]