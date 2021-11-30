FROM open-liberty:21.0.0.7-full-java11-openj9

COPY server.xml /config/
COPY spring-liberty-plain.war /config/apps/

USER 1001
EXPOSE 9080
