FROM tomcat:8.0
LABEL author="malli"
ADD openmrs.war /usr/local/tomcat/webapps/openmrs.war
EXPOSE 8080
CMD [ "catalina.sh","run" ]


# Build the image "docker build -t openmrs:2.1.2"
# docker tag openmrs:2.1.2 <>docker username>/openmrs:2.1.2
#docker login
# docker push
# 