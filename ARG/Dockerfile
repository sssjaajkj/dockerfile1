ARG version
FROM almalinux:${version:-8}
# how to know os of the system
#RUN cat /etc/*release
ARG COURSE
ARG TRAINER
ARG Duration=120HRS
ENV Duration=${Duration}
RUN echo "Course is : ${COURSE}, TRAINER is ${TRAINER}, Duration is : ${Duration}"
CMD [ "sleep","60"]