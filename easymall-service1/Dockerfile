FROM java:8-alpine
COPY ./app.war /tmp/app.war
EXPOSE 8080
ENTRYPOINT java -Dspring.cloud.nacos.server-addr=nacos:8848 -jar /tmp/app.war