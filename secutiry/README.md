# Commnads

kubectl config --kubeconfig=/root/my-kube-config use-context research

kubectl config --kubeconfig=/root/my-kube-config current-context

kubectl get roles

kubectl get rolebindings

kubectl describe role developer 

kubectl describe rolebinding rolebindingname

kubectl auth can-i create deployments

kubectl auth can-i delete nodes

kubectl auth can-i delete nodes --as dev-user
