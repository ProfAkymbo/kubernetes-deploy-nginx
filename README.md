# kubernetes-deploy-nginx
This repo deploys an nginx service exposed on port 80


### To deploy an NGINX service (and expose the service on port 80), run the following commands:
```
 sudo kubectl run --image=nginx nginx-app --port=80 --env="DOMAIN=cluster"

 sudo kubectl expose deployment nginx-app --port=80 --name=nginx-http
```
### To see the services listed, use the following command:
```
 sudo docker ps -a
```
