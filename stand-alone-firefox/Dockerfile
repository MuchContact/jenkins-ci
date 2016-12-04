FROM selenium/standalone-firefox:3.0.1-aluminum
RUN sudo locale-gen zh_CN.UTF-8
ENV LANG zh_CN.UTF-8
ENV LANGUAGE=zh_CN:zh
ENV LC_ALL=zh_CN.UTF-8
RUN sudo apt-get -y update
RUN sudo apt-get -y install openjdk-8-jdk
ENV TZ=Asia/Shanghai
