FROM amazonlinux:2

RUN yum update -y && yum install -y make gcc-c++
RUN curl -sL https://rpm.nodesource.com/setup_12.x | bash -
RUN yum install -y nodejs

WORKDIR /src

RUN npm i -g npm@^6.0.0

CMD ["node"]
