Taint Node
kubectl taint nodes ip-192-168-43-212.ec2.internal hardware=gpu:NoSchedule
Untaint Node
kubectl taint nodes ip-192-168-43-212.ec2.internal hardware=gpu:NoSchedule-

kubectl taint nodes ip-192-168-43-212.ec2.internal hardware=gpu:NoExecute
kubectl taint nodes ip-192-168-43-212.ec2.internal hardware=gpu:NoExecute-
To add the labels
kubectl label nodes ip-192-168-43-212.ec2.internal hardware=gpu