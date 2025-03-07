Taint the node
```
kubectl taint nodes <node-ip-address> <key1>=<value1>:NoSchedule
```

ex:
```
kubectl taint nodes ip-192-168-17-52.ec2.internal hardware=GPU:NoSchedule
```