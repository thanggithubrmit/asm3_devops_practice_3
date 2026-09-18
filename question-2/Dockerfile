FROM tomcat:latest
RUN rm -rf /usr/local/tomcat/webapps/*
COPY ./my-app.war /usr/local/tomcat/webapps/ROOT.war
EXPOSE 8080
CMD ["catalina.sh", "run"]
