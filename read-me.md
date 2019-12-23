####create deployment
kubectl apply -f <filename>
####create ingress
kubectl apply -f <filename>
####enable ingress
kubectls addons enable ingress
####expose deployment as a NodePort
kubectl expose deployment <name> --port-target=<port> --type=NodePort

