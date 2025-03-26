FROM jenkins/jenkins:lts
USER root
RUN apt-get update && \
    apt-get install -y python3 python3-pip && \
    ln -s /usr/bin/python3 /usr/bin/python
RUN apt -y install python3.11-venv
USER jenkins