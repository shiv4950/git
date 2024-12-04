https://github.com/hkhcoder/vprofile-project.git
minikube start
kubectl get po -A
kubectl create deployment hello-minikube --image=kicbase/echo-server:1.0
kubectl expose deployment hello-minikube --type=NodePort --port=8080
kubectl get services hello-minikube
minikube service hello-minikube
docker ps
kubectl get pods


