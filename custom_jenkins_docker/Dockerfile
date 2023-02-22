FROM jenkins/jenkins:lts
USER root
RUN sh -c "$(curl https://raw.githubusercontent.com/abotias/scripts/master/install_docker_compose.sh)"
RUN usermod -aG docker jenkins
