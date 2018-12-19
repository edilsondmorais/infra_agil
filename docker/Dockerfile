FROM debian
MAINTAINER edilsondmorais@yahoo.com.br

RUN apt clean all
RUN apt update

RUN apt install apache2 linuxlogo -y
#COPY pasta_origem pasta_container
ADD https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/2000px-Tux.svg.png /root/docker.png

#ENV VARIAVEL=1234
EXPOSE 80

#CMD
ENTRYPOINT ["/bin/bash"]

