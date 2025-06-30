## Install Helm
```
curl https://raw.githubusercontent.com/helm/helm/master/scripts/get-helm-3 | bash
helm repo add bitnami https://charts.bitnami.com/bitnami
helm repo update
helm version
```

## Creation des Charts Helm
```
helm create mysql
helm create worpress
helm install my-wordpress ./mysql
helm install my-wordpress ./wordpress
```
