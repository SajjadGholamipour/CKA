# Preface
This Git repository contains supporting files for my "Certified Kubernetes Administrator (CKA)" video course. See https://sandervanvugt.com for more details. 
# Requirements
In lab environment, we consider 3 virtual machine, using Ubuntu LTS server 20.4 or later (22.4 is recommended).
* 1 controller(master) node
* 2 worker nodes
  
In this course you need to have your own lab environment. This lab environment should consist of 3 virtual machines, using Ubuntu LTS server 20.4 or later (22.4 is recommended)
Make sure the virtual machines meet the following requirements
* 2 vCPUs
*	2GB RAM
*	20 GB disk space
*	No swap
# IP Plan
* controller: 10.169.50.135
* worker1: 10.169.50.87
* worker2: 10.169.50.163
# Installation Guide



# Updates

JUNE 2023 NOTE: The Calico network plugin has been changing a lot lately. I recommend using the following command to install it:

kubectl apply -f https://raw.githubusercontent.com/projectcalico/calico/v3.26.0/manifests/calico.yaml

For more information, see the instructions at https://docs.tigera.io/calico/latest/getting-started/kubernetes/quickstart to install the Calico network plugin. 
