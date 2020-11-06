FROM maven:3.6.3-jdk-11

RUN echo hello > hello.txt
RUN mvn --version
RUN mkdir /test_result
ADD target/ /test_result
  
EXPOSE 8080
