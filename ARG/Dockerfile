ARG version
FROM almalinux:${version}
# how to know os of the system
#RUN cat /etc/*release
ARG COURSE
ARG TRAINER
ENV Duration=120HRS
RUN echo "Course is : ${COURSE}, TRAINER is ${TRAINER}, Duration is : ${Duration}"
CMD [ "sleep","60"]