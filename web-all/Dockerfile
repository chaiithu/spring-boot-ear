FROM jboss/wildfly:latest
WORKDIR /koti
COPY **/*.ear .
CMD ["/opt/jboss/wildfly/bin/standalone.sh","-b","0.0.0.0"]
EXPOSE 8080
