# rancher-k8s-security
Rancher is deployed on a Single Node (AWS EC2) using Docker (left).

![Rancher Deployment](rancher-architecture-separation-of-rancher-server-b32508a12beee49d72836caa5469e585.svg)

I followed the "PHP Guestbook application with Redis" example in the Kubernetes Documentation. The cluster comprises three nodes, with one master and two workers, all of which are AWS EC2 instances. For the Load Balancer, I utilized the EC2 Application Load Balancer (ALB).

![Cluster Deployment](kubernetes-constructs-concepts-architecture.jpg)
