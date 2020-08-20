# wishlist
Sample wishlist application to demo microservices with containers running in Kubernetes.

> kubectl apply -f https://projectcontour.io/quickstart/contour.yaml

> helm repo add stable http://mirror.azure.cn/kubernetes/charts/
> helm repo update
> helm install prom-demo stable/prometheus -f prometheus-values.yaml
> kubectl get deployments -w
> minikube service prom-demo-prometheus-server

