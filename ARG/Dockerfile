ARG VERSION
FROM almalinux:${VERSION:-9}
ARG COURSE="DOCKER"\
    TRAINER="SIVA"\
    DURATION="11HRS"
ENV COURSE=${COURSE}
RUN echo "Trainer: ${TRAINER}, duration: ${DURATION},course :${COURSE},version=${VERSION}"
CMD ["sleep","1000"]