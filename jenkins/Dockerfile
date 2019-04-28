FROM jenkins/jenkins:lts

ENV PLUGINS_FORCE_UPGRADE=ture

COPY plugins.txt /usr/share/jenkins/ref/plugins.txt

RUN /usr/local/bin/install-plugins.sh < /usr/share/jenkins/ref/plugins.txt


