FROM tomcat:9.0.79-jre11-temurin-focal

LABEL maintainer="phithon <root@leavesongs.com>"

RUN sed -i 's/securerandom\.source=file:\/dev\/random/securerandom.source=file:\/dev\/.\/urandom/g' $JAVA_HOME/lib/security/java.security