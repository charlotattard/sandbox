# sandbox
This is a sandbox setup


To expose the deployment I ran the below command


kubectl expose deployment hello-minikube1 --type=NodePort --port=8080


minikube service hello-minikube1 --url


Then used a proxy_pass as described in cms.conf to proxy_pass the application.


The problem is that I get HTTP 403 Error
