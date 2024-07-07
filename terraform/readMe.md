
# minikube
-> minikube start
# terraform
-> terrform init
-> terrform apply

# open terminal 
-> kubectl secrete -n argocd
-> kubectl get secrets argocd-initial-admin-secret -o yaml -n argocd
-> echo [copy password from secrete] | base64
-> kubectl port-forward svc/argocd-server -n argocd 8080:80