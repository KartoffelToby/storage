FROM rancher/storage-nfs:v0.9.0
COPY nfs/rancher-nfs common/* /usr/bin/
CMD ["start.sh", "storage", "--driver-name", "rancher-nfs"]
