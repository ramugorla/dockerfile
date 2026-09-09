# FROM almalinux:9 
# ENV course="Devops" \
#     trainer="siva" \
#     duration="120"
# RUN echo "Hello ${trainer}" > /tmp/devops.txt
# CMD ["sleep", "100"]

# we can overiden ENV variables by using below 
#  docker build -t arg:1.0.0 --progress=plain --no-cache --build-arg tariner=ramu .


ARG version 
FROM almalinux:${version:-9}
ARG USERNAME=laxman
ENV USERNAME=${USERNAME}
#ENV USERNAME=$USERNAME
RUN echo "Hello ${USERNAME}, Base version ${version}" > /tmp/devops.txt
CMD ["sleep", "100"]