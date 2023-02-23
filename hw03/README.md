Порядок запуска

minikube start

minikube tunnel

helm install postgres bitnami/postgresql -f ./values-pg.yaml

kubectl apply -f ./Secret.yaml

kubectl apply -f ./CM.yaml

kubectl apply -f ./init-job.yaml

kubectl apply -f ./Deployment.yaml

kubectl apply -f ./Service.yaml

kubectl apply -f ./Ingress.yaml