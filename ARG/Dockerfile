ARG version 
FROM almalinux:${version:-8}
# cat /etc/*release 
ARG COURSE=docker
ARG TRAINER=sivakumar
ARG DURATION=120HRS
ENV duration=${DURATION}
RUN echo "course is: ${COURSE} ,Trainer is: ${TRAINER}, duration is: ${duration}"
CMD ["sleep","100"]