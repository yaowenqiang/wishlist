# wishlist
Sample wishlist application to demo microservices with containers running in Kubernetes.

> echo  'linuxhint.com' | base64
> echo "aG9zdG5hbWU9MTkyLjE2OC4xLjE7cGFzc3dvcmQ9MTIzNDU2Cg==" | base64 --decode


> livenessProbe

> https://kubernetes.io/zh/docs/tasks/configure-pod-container/configure-liveness-readiness-startup-probes/
> 
> kubectl apply -f https://projectcontour.io/quickstart/contour.yaml

> helm init
> helm init -i registry.cn-hangzhou.aliyuncs.com/google_containers/tiller:v3.2.4 --stable-repo-url https://kubernetes.oss-cn-hangzhou.aliyuncs.com/charts
> helm repo add stable http://mirror.azure.cn/kubernetes/charts/
> helm repo update
> helm install prom-demo stable/prometheus -f prometheus-values.yaml
> kubectl get deployments -w
> minikube service prom-demo-prometheus-server

> minikube start --feature-gates=EphemeralContainers=true
> kubectl alpha debug -it hotrod-deployment-646588f449-n4k4w  --image=busybox

