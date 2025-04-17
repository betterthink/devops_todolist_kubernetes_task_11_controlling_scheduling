# Testing Django ToDo app
## Validating labels
To validate labels run this command:
```bash
kubectl get nodes --show-labesl
```
## Validating affinity rules
```bash
kubectl get podes -n todoapp -o wide
```
```bash
kubectl get podes -n mysql -o wide
```