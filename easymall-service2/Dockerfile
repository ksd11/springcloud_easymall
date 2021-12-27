FROM java:8-alpine
COPY ./app.war /tmp/app.war
EXPOSE 8081
ENTRYPOINT java -Dspring.cloud.nacos.server-addr=nacos:8848 -Dserver.port=8081 -jar /tmp/app.war