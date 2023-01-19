# syntax=docker/dockerfile:1.4

FROM ubuntu:22.10 AS builder

FROM builder as dev-envs
RUN <<EOF
apt-get update
apt-get upgrade
EOF

ENTRYPOINT ["tail"]
CMD ["-f","/dev/null"]
# RUN apt-get install -y lxde-core 
# apt-get install lxde-core
# apt-get install xrdp
# apt install ubuntu-desktop
# apt install xrdp
# systemctl enable xrdp