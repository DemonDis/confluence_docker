FROM atlassian/confluence-server:7.5.0-ubuntu

COPY atlassian-extras-decoder-v2-3.4.1.jar /opt/atlassian/confluence/confluence/WEB-INF/lib/

# Disable JMX to avoid MBean registration conflicts
RUN echo 'export CATALINA_OPTS="$CATALINA_OPTS -Dconfluence.jmx.disabled=true -Dspring.jmx.enabled=false -Dcom.sun.management.jmxremote=false"' >> /opt/atlassian/confluence/bin/setenv.sh