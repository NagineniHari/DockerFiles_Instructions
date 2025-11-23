FROM almalinux:9
# RUN cd /tmp
# RUN pwd
RUN mkdir /app
WORKDIR /app
RUN pwd
RUN echo "Hello Docker" > hello.txt
CMD ["sleep","1000"]


## cd /tmp will not work here we have to use WORKDIR , cd command will change and again it show root only
## Commands that we give after WORDIR will run in /app folder even we login to the service we will launch to /app directly