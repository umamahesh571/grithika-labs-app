# Grithika Labs DevOps Demo App

Build:
mvn clean package

Run:
java -jar target/grithika-app-1.0.jar

Docker:
docker build -t grithika-app:v1 .

Kubernetes:
kubectl apply -f k8s/
