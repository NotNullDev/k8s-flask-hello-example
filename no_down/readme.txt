

Steps to run with minikube:
    1. Start minikube:
        minikube start
    2. kubectl apply -f deployment_flas.yml
    3. kubectl apply -f service_flask.yml
    4. minikube service list # this command shows services ip addresses and ports