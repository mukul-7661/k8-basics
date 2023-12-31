To run locally:

1. Clone the repo
2. Install [Docker](https://docs.docker.com/engine/install/).
3. Install [minikube](https://minikube.sigs.k8s.io/docs/start/).
4. minikube start
5. cd k8-basics
6. kubectl apply -f mongo-config.yaml
7. kubectl apply -f mongo-secret.yaml
8. kubectl apply -f mongo.yaml
9. kubectl apply -f web-app.yaml
10. kubectl get all - to verify that all components are created.
11. minikube ip -> to get ip address of minikube
12. Visit {minkube_ip}:30100 in browser to see the application live.
