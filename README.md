# Dev-ops-tools

Hi everyone !

 install docker /
    build the docker file (jenkins_with_docker) /
    run the jenkins with docker client image /
    && map the path of the docker daemon inside your pc and the docker daemon which in the jenkins with docker image (container)

docker build . -f jenkins_with_docker -t jenkins_docker

docker run -d -p 8080:8080 -v /var/run/docker.sock:/var/run/docker.sock jenkins_docker 


finally build the nodejs app!

