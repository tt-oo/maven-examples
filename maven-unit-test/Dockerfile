FROM alpine:3.12

RUN echo hello > hello.txt
RUN ls -al
RUN mkdir /test_result
ADD target/ /test_result
  
EXPOSE 8080
