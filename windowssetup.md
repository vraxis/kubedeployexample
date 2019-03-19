To install skaffold, prereqs on windows

- VirtualBox
- Minikube (opt to use docker daemon running in minikube so you dont need an external registry)
- Kubectl



Install kubectl
https://kubernetes.io/docs/tasks/tools/install-kubectl/
```
Install-Script -Name install-kubectl -Scope CurrentUser -Force
install-kubectl.ps1 [-DownloadLocation <path>]
```
Verify it worked
```
kubectl version
```

https://kubernetes.io/docs/tasks/tools/install-minikube/


