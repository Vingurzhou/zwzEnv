FROM golang:1.17

# $GOPATH/bin添加到环境变量中
#ENV PATH $GOPATH/bin:$PATH

# 日志目录
RUN mkdir /var/log/golang

# 设置工作目录
WORKDIR /usr/src/code


RUN go env -w GO111MODULE=auto
RUN go env -w GOPROXY=https://goproxy.io,direct

#RUN go build

#CMD zwo-admin server -c config/settings.yml -p 8100 -m dev

#EXPOSE 8100