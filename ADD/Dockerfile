FROM almalinux:9
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
EXPOSE 80/tcp
ADD payment-v3.zip /tmp/
COPY index.html /usr/share/nginx/html/
ADD https://raw.githubusercontent.com/naginenihari/DevSecOps-Notes/refs/heads/main/ansible%20new%20server.txt /tmp/DevSecOps.txt#ADD sample-2.tar /tmp/
ADD sample-1.tar /tmp/
CMD ["nginx","-g","daemon off;"]
#CMD ["sleep","150"]



## COPY & ADD is used to copy the files and directories from local to image.
## The index.html should be where the dockerfile is created 

##ADD is having extra capabilities than COPY
## ADD can download the file from internet/remote.[Copied something from github or any source to /tmp]
## ADD can untar the files.[sample-1.tar file is in my local Dockerfile from here copying it into the /tmp ]