https://github.com/hkhcoder/vprofile-project.git
minikube start
kubectl get po -A
kubectl create deployment hello-minikube --image=kicbase/echo-server:1.0
kubectl expose deployment hello-minikube --type=NodePort --port=8080
kubectl get services hello-minikube
minikube service hello-minikube
docker ps
kubectl get pods


date pattern=yy-MM-dd-HHmm
mkdir -p verions
cp target/vprofile-v2.war
versions/vprofile-V$BUILD_ID_$BUILD_TIMESTAMP.war



**/*.war

sudo docker build -t nodejsapp .
sudo docker run -d -p 3000:3000 nodejsapp
