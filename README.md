 Training Project for Running Container Clusters with Kubernetes
 ===================================================================

## Description

Ansible playbook to sets up a Kubernetes Cluster with 1 Master and 2 Minions on Centos7

## Snippets

* kubectl create -f nginx.yaml
* kubectl port-forward nginx :80 &
 [user@tillkuhn1 ~]$ wget -qO- http://localhost:35046
 I1101 08:06:07.407626    6154 portforward.go:247] Handling connection for 35046
 [user@tillkuhn1 ~]$ wget -qO- http://localhost:35046 |grep Welcome
 I1101 08:07:29.654079    6154 portforward.go:247] Handling connection for 35046
 <title>Welcome to nginx!</title>
 <h1>Welcome to nginx!</h1>
