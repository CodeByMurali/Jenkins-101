FROM jenkins/jenkins

COPY ansible.cfg /var/jenkins_home/.ansible.cfg

USER root

RUN apt update

RUN apt-get install -y python3

RUN apt-get install -y ansible

ENV ANSIBLE_CONFIG="/var/jenkins_home/.ansible.cfg"

USER jenkins