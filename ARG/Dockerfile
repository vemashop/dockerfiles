ARG version
FROM almalinux:${version:-9}
# FROM almalinux:9
ENV course="Devops with siva" \
    trainer="siva" 
    
ARG USERNAME=sivakumar
# ENV username="${USERNAME}"
RUN echo "hello : ${USERNAME}, version is ${version}" > /tmp/devops.txt
CMD ["sleep", "100"]