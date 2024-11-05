FROM tomcat:latest
RUN cp -R /usr/local/tomcat/webapps.dist/* /usr/local/tomcat/webapps

# Create IMAGE --- ~]# docker build -t demotomcat .
# Create CONTAINER --~]# docker run -d --name demotomcat-container -p 6065:8080 demotomcat