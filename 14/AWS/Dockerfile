FROM amazonlinux:2

RUN yum update -y && yum install -y make gcc-c++
RUN curl -sL https://rpm.nodesource.com/setup_14.x | bash -
RUN yum install -y nodejs

WORKDIR /src

RUN npm i -g npm

CMD ["node"]
