# fedora32 Ansible Test Image

<a href="https://github.com/MonolithProjects/docker-systemd-fedora32/actions"><img src="https://github.com/MonolithProjects/docker-systemd-fedora32/workflows/Dockerfile%20test/badge.svg?branch=master"/></a>
<a href="https://hub.docker.com/repository/docker/monolithprojects/systemd-fedora32"><img src="https://img.shields.io/microbadger/layers/monolithprojects/systemd-fedora32"/></a>
<a href="https://hub.docker.com/repository/docker/monolithprojects/systemd-fedora32"><img src="https://img.shields.io/docker/pulls/monolithprojects/systemd-fedora32"/></a>
<a href="https://hub.docker.com/repository/docker/monolithprojects/systemd-fedora32"><img src="https://img.shields.io/docker/cloud/automated/monolithprojects/systemd-fedora32?maxAge=2592000"/></a>

Fedora32 docker image with enabled systemd. I am using it with Molecule for Ansible role testing.

## Tags

- `latest`: Latest version of the image

## How-to

  1. Pull image with command `docker pull monolithprojects/systemd-fedora32:latest`  
  2. Run the container from the image: `docker run --detach --privileged --volume=/sys/fs/cgroup:/sys/fs/cgroup:ro monolithprojects/systemd-fedora32:latest`  

## License

MIT
