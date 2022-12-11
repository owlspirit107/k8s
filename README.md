# k8s
k8s dumps

# to taint a node
kubectl taint nodes ip-192-168-17-27.ec2.internal  app=jenkins:NoSchedule

# to apply label to node
kubectl label nodes ip-192-168-17-27.ec2.internal  app=jenkins
