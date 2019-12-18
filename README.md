# k8s-cluster-demo

This is an implementation of https://www.digitalocean.com/community/tutorials/how-to-create-a-kubernetes-cluster-using-kubeadm-on-ubuntu-18-04

# problems & solutions
Virtual machines provisioned in a public cloud may need an inbound firewall exception for ports 30000-65535 so that traffic from localhost can reach the cluster. Typically these ports are disabled for security reasons.