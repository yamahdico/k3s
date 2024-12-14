# k3s


## kubectl alias k completion

```bash 
echo 'alias k=kubectl' >>~/.bashrc (add alias to shell)
echo 'source <(kubectl completion bash)' >>~/.bashrc (add completion)
echo 'complete -F __start_kubectl k' >>~/.bashrc (make them work together)
```
## Installed PHP modules 
kubectl exec -it <php-pod-name> -- php -m


## Docker vs CRIctl
crictl ps
docker ps


## kubectl alias k completion
kubectl apply -f mysql-deployment.yaml
kubectl apply -f php-deployment.yaml
kubectl apply -f php-ingress.yaml

