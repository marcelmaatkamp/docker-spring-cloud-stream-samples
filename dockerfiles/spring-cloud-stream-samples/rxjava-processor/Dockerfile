FROM maven:3-jdk-8
# RUN bash -c '([[ ! -d $JAVA_SECURITY_DIR ]] && ln -s $JAVA_HOME/lib $JAVA_HOME/conf) || (echo "Found java conf dir, package has been fixed, remove this hack"; exit -1)'
 
VOLUME /root/.m2
VOLUME /application
WORKDIR /application

CMD ["gradle","bootRun"]
