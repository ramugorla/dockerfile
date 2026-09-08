FROM almalinux:9 
RUN mkdir /tmp/work-demo 
#RUN cd /tmp/work-dir-demo   cd will not work in the container
WORKDIR /tmp/work-demo
RUN pwd 
RUN echo "Hello i am workdir" > hello.txt 
CMD ["sleep", "100"]