# Minikube-Mongo-Mongo-Express-setup
A simple kubernetes local deployment of mongo db and mongo-express using deployments and services.

STEPS TO RUN IT LOCALLY :- (make sure you have minikube up and running)

1. kubectl apply -f <all-files.yaml>
2. kubectl get pods #check if all pods are up and running
3. minikube service mongo-service
