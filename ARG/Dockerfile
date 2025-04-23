ARG version
FROM amazonlinux:${version:-9}
ARG cource="DevOps with AWS" \
    duration="60 minites"
ENV duration=$duration
RUN echo "cource:$cource, duration:$duration, version:$version"
CMD [ "sleep", "100" ]
