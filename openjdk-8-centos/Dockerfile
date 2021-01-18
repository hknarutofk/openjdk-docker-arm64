FROM centos:7

RUN yum install --setopt=tsflags=nodocs java-1.8.0-openjdk java-1.8.0-openjdk-devel -y && yum clean all
RUN localedef -c -f UTF-8 -i zh_CN zh_CN.utf8 #配置显示中文
ENV LC_ALL zh_CN.utf8 #设置环境变量
