# To execute Dockerfile
 -- From the same diretory the Dockerfil is located execute: 
    [~]# docker build -t mytomcat .

# Once Dockerfile is read and executed, image will be local repo
   [~]# docker image ls
    REPOSITORY   TAG       IMAGE ID       CREATED         SIZE
    mytomcat     latest    9be4eda07580   9 minutes ago   515MB

# Create container named mytomcat-server from mytomcat image 
    [~]# docker run -d --name mytomcat-server -p 8083:8080 mytomcat 

# Once container start
    -- Verify that you are able to access tomcat on http:\\host-ip-address:8083


