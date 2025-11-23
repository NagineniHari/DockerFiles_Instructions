ARG VERSION
FROM almalinux:${VERSION:-9}
ARG COURSE="DOCKER"\
    TRAINER="SIVA"\
    DURATION="11HRS"
ENV COURSE=${COURSE}
RUN echo "Trainer: ${TRAINER}, duration: ${DURATION},course :${COURSE},version=${VERSION}"
CMD ["sleep","1000"]




## ARG instruction will pass the arguments while building the image. We are not hard coding and pass the values in command.
## ENV can pass the arguments while building image and running container.

##To pass the user name during building an image
## docker build -t <image_name>:<version> --build-arg <key>=<value> .
## docker build -t arg:v1 --build-arg course=DOCKER
##Run command will take print the values from ARG and to ARG instruction we are passing via commnad during build.