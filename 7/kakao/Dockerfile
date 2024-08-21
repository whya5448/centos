FROM centos:7

RUN sed -i  \
    -e 's/mirror.centos.org/mirror.kakao.com\/centos/' \
    -e 's/mirrorlist=/#mirrorlist=/' \
    -e 's/#baseurl=/baseurl=/' \
    /etc/yum.repos.d/CentOS-Base.repo