ARG VERSION
FROM almalinux:${VERSION:-9}
ARG COURSE="DOCKER" \
    TRAINER="SIVAKUMAR" \
    STUDENT="ARJUN"
ENV COURSE=${COURSE}
RUN echo "Trainer: ${TRAINER}, Student: ${STUDENT}, Course: ${COURSE}, Version: ${VERSION}"
CMD ["sleep", "1000"]