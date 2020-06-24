# Docker build usage:
# 	docker build . -t sodafoundation/controller:latest
# Docker run usage:
# 	docker run -d --net=host -v /etc/opensds:/etc/opensds sodafoundation/controller:latest

FROM ubuntu:16.04
MAINTAINER Leon Wang <wanghui71leon@gmail.com>

COPY osdslet /usr/bin

# Define default command.
CMD ["/usr/bin/osdslet"]
