# Docker examples for quickly starting/testing apps in an ecosystem

| Project | hub.docker.com | Github |
| --- | --- | --- |
| Jenkins | jenkins/jenkins | https://github.com/jenkinsci/docker |
| Elasticsearch/Logstash/Kibana | docker.elastic.co/appName | https://github.com/elastic/stack-docker |
| Java | library/openjdk aka openjdk | https://github.com/docker-library/official-images/library/openjdk |
| Python | library/python aka python | https://github.com/docker-library/official-images/library/openjdk |


OpenShift by RedHat for detecting this (Otto deprecated from Hashicorp)
https://github.com/openshift/source-to-image

Cheating on top two using https://ifritltd.com/2017/08/22/dockerizing-jenkins-build-logs-with-elk-stack-filebeat-elasticsearch-logstash-and-kibana/

Docker
https://docs.docker.com/install/
`docker run -it --rm hello-world`
Ports with `-p host:guest`
Volumes with `-v host:guest` or `--mount type=bind,source=$(pwd),target=/src`

Docker-compose
https://docs.docker.com/compose
Docker-compose allows "composing" multiple containers together into "stacks", while the Swarm tool enables running these stacks across multiple hosts (similar to Kubernetes).
