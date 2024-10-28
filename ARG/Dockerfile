ARG version 
FROM almalinux:${version:-8}
#ARG username means variable thesukuntunam
ARG username
#painavuna username ki value ni supply cheyali .so adduser whatever you value supply run  
RUN adduser $username
USER $username
ARG COURSE
ARG TRAINER
RUN echo "Course: ${COURSE}, Trainer: ${TRAINER}, version: ${version}"
ENV COURSE=${COURSE}
ENV TRAINER=${TRAINER}
CMD [ "sleep", "100" ] 