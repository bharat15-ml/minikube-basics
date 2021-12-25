# Minikube-basics:

minikube is local Kubernetes, focusing on making it easy to learn and develop for Kubernetes. All you need is Docker (or similarly compatible) container or a Virtual Machine environment, and Kubernetes is a single command away: minikube start

# Basic requirements:
1. 2 CPUs or more
2. 2GB of free memory
3. 20GB of free disk space
4. Internet connection
5. Container or virtual machine manager, such as: Docker, Hyperkit, Hyper-V, KVM, Parallels, Podman, VirtualBox, or VMWare Workstation.

This repo is a quick start guide to create local kubernetes cluster on your system/virtual machine also it includes steps needed for helm installation.

Required steps to create one node Minikube kubernetes cluster and helm installation are given below:
1. install virtual machine on your host system, here we have used Windows10 as host system.
2. install ubuntu-20.04 operating system on your virtual machine, with 40GB Hard disk, 3GB RAM and 2 VCPU.
3. Enable Virtualization on your VM settings otherwise it will give some unexpected error while creating Minikube cluster (added snapshot of required setting i.e. given in, VM-Settings-Minikube.JPG).
4. Install Minikube and Create Minikube cluster.
5. Install Helm.

# follow below code section files in sequences to setup and install minikube cluster:
1. install-Vmware Workstation 16 player
2. minikube-install
3. minikube-start
4. kubernetes-install
5. helm install

With instructions given in files, you should able to setup and run one node minikube cluster in your VM Machine.

References:
1. https://docs.bitnami.com/kubernetes/get-started-kubernetes/
2. https://minikube.sigs.k8s.io/docs/start/
3. https://computingforgeeks.com/how-to-install-minikube-on-ubuntu-debian-linux/
