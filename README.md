# sbodahomelab

Created 3 node cluster 1 master and 2 worked nodes using kubeadm

Added Calico CNI for Network within the cluster

Used Metal LB for LoadBalancing for apps thats going to be deployed

Made sure to setup the Node to Node connection

Remove the lister section from Metallb-Native.yml file

=> Use custom-resource-yml file for calico deployment using helm