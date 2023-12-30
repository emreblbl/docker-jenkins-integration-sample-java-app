# A Containerized Hello World Java deployment with Docker 

a very simple rest-api-hello-world java application with Spring Boot and Maven, containerized with dockerfile, ready to build and deployed with a very simple way.

## How to Build
```
docker build -t hello-world-java-docker .
```  

## How to Run
```
docker run -it hello-world-java-docker
```

## Blog Post
```
https://edwin.baculsoft.com/2020/07/building-containerized-images-on-openshift-4-and-push-the-result-to-third-party-image-registry/
```



## Port forwarding or Nodeport 

kubectl port-forward service/sample-app-service 8080:80 -n sample
Forwarding from 127.0.0.1:8080 -> 8080
Forwarding from [::1]:8080 -> 8080
Handling connection for 8080