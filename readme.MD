Taint the node
```
kubectl taint nodes <node-ip-address> <key1>=<value1>:NoShedule
```

ex:
```
kubectl taint nodes ip hardware=GPU:Noshedule
```