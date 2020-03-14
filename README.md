cd /tmp

tar -xf kubepackage.tar

cd kubepackage/

yum install -y https://download.docker.com/linux/centos/7/x86_64/stable/Packages/containerd.io-1.2.5-3.1.el7.x86_64.rpm

yum install -y ftp://bo.mirror.garr.it/1/slc/centos/7.1.1503/extras/x86_64/Packages/container-selinux-2.9-4.el7.noarch.rpm

yum install -y https://download.docker.com/linux/centos/7/x86_64/stable/Packages/docker-ce-18.09.5-3.el7.x86_64.rpm

yum install -y https://download.docker.com/linux/centos/7/x86_64/stable/Packages/docker-ce-cli-18.09.5-3.el7.x86_64.rpm

yum install -y https://download.docker.com/linux/centos/7/x86_64/stable/Packages/docker-ce-18.09.5-3.el7.x86_64.rpm

yum install -y ebtables-2.0.10-16.el7.x86_64.rpm

yum install -y socat-1.7.3.2-2.el7.x86_64.rpm

yum install -y libnetfilter_queue-1.0.2-2.el7_2.x86_64.rpm libnetfilter_cttimeout-1.0.0-6.el7_7.1.x86_64.rpm libnetfilter_cthelper-1.0.0-10.el7_7.1.x86_64.rpm

yum install -y 06400b25ef3577561502f9a7a126bf4975c03b30aca0fb19bb636f870ab93876-kubectl-1.17.4-0.x86_64.rpm 0767753f85f415bbdf1df0e974eafccb653bee06149600c3ee05b903bdc897ba-kubeadm-1.17.4-0.x86_64.rpm 0c45baca5fcc05bb75f1e953ecaf85844efac01bf9c1ef3c219f2b41eade3168-kubelet-1.17.4-0.x86_64.rpm 14bfe6e75a9efc8eca3f638eb22c7e2ce759c67f95b43b16fae4ebabde1549f3-cri-tools-1.13.0-0.x86_64.rpm 548a0dcd865c16a50980420ddfa5fbccb8b59621179798e6dc905c9bf8af3b34-kubernetes-cni-0.7.5-0.x86_64.rpm

