# CentOS 7 Ansible Docker Image

CentOS 7 Docker container for Ansible playbook and role testing.

## How to Build

This image is built on CentOS Base Images.

```
# Build docker image
docker build -t centos7:latest .
# Tag image
docker tag ansible-centos stackware/ansible-centos:latest
#Login to Docker Hub
docker login
#Upload/Push Docker image
docker push stackware/ansible-centos:latest
```

## Author

martin@it-kombinat.org
