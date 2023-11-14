FROM ubuntu:latest
RUN add-apt-repository ppa:linuxuprising/java
RUN apt-get update
RUN apt-get install -y oracle-java16-installer
RUN apt-get clean 
RUN rm -rf /var/lib/apt/lists/*