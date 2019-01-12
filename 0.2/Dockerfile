FROM centos:7
MAINTAINER Farkhod Sadykov
RUN yum -y install epel-release
RUN yum install -y https://centos7.iuscommunity.org/ius-release.rpm
RUN yum install -y python36u python36u-libs python36u-devel python36u-pip
RUN yum -y install python-devel libxslt-devel vim libffi-devel openssl-devel mariadb-devel gcc wget && yum clean all
RUN rm -rf /var/cache/yum

