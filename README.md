# centos7-ansible

## Run docker with systemd
sudo docker run --privileged -ti -v /sys/fs/cgroup:/sys/fs/cgroup:ro -p 80:80 centos7-ansible

## Exec bash to get shell
sudo docker exec -it [CONTAINER_ID] /bin/bash
