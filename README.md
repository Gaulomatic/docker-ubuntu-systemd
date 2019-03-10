# docker-ubuntu-systemd
## Run:
docker run --rm --name systemd --security-opt seccomp=unconfined --tmpfs /run --tmpfs /run/lock -v /sys/fs/cgroup:/sys/fs/cgroup:ro -t gaulomatic/ubuntu-systemd
