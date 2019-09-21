FROM ubuntu:16.04 

COPY script.sh .
RUN apt-get update -y; apt-get install curl -y
RUN chmod 777 ./script.sh
CMD ["./script.sh"]
