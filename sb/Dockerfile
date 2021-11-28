FROM alpine
RUN apk update
RUN apk add openjdk8
RUN apk add maven -l
RUN apk add git -l
WORKDIR /tmp/
RUN git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello
WORKDIR /tmp/boxfuse-sample-java-war-hello
RUN mvn package