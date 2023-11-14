FROM tomcat:8

COPY sample.war /usr/local/tomcat/webapps/sample.war

RUN useradd -ms /bin/bash testuser

USER testuser

CMD ["/usr/local/tomcat/bin/catalina.sh", "run"]
