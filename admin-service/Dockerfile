FROM java:8-alpine
COPY ./app.jar /tmp/app.jar
ENTRYPOINT java -Dspring.cloud.nacos.server-addr=nacos:8848 -jar /tmp/app.jar