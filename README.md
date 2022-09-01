# csi-proxy-builder

For a Kubernetes cluster to mount SMB shares in Windows nodes, it is required to be installed 
[csi-proxy](https://github.com/kubernetes-csi/csi-proxy) on the Windows host operating systems. Kubernetes SMB driver 
[csi-driver-smb](https://github.com/kubernetes-csi/csi-driver-smb#container-images--kubernetes-compatibility) depends on 
csi-proxy on Windows nodes. 

# Note this repo is public:
Csi-proxy is an open source project, mostly maintained by Microsoft. To install csi-proxy on EC2 instances at boot time, 
a publicly accessible download link is required. Currently, csi-proxy developers do not distribute built binaries, see: 
https://github.com/kubernetes-csi/csi-proxy#build  This repository builds and publishes binaries as GitHub release 
artifacts.
