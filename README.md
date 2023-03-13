# DevOps
After running install-k3s.sh:

The K3s service will be configured to automatically restart after node reboots or if the process crashes or is killed
Additional utilities will be installed, including kubectl, crictl, ctr, k3s-killall.sh, and k3s-uninstall.sh
A kubeconfig file will be written to /etc/rancher/k3s/k3s.yaml and the kubectl installed by K3s will automatically use it
