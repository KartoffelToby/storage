FROM rancher/storage-nfs:v0.9.0
RUN apt-get update -y && apt-get install -y cifs-utils
COPY ./rancher-nfs common/* /usr/bin/
CMD ["start.sh", "storage", "--driver-name", "rancher-nfs"]
