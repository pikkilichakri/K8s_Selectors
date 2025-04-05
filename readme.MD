# Selectors

Taint the nodes

...
kubectl taint nodes ip-10-0-0-10.ec2.internal  hardware=gpu NoSchedule
...

Untaint the nodes

...
kubectl taint nodes ip-10-0-0-10.ec2.internal hardware=gpu NoSchedule-
...

Label nodes

...
kubectl lable nodes ip-10-0-0-10.ec2.internal hardware=gpu
...

Ref: https://kubernetes.io/docs/tasks/configure-pod-container/assign-pods-nodes
