# Dockerizing a simple golang webapp project
https://dev.to/heroku/deploying-your-first-golang-webapp-11b3 

https://hub.docker.com/_/golang 

https://itnext.io/docker-container-as-an-executable-to-process-images-using-go-golang-5233f9bd3bf7 

https://itnext.io/docker-container-as-an-executable-to-process-images-using-go-golang-5233f9bd3bf7

https://bitfieldconsulting.com/golang/docker-image 


---
$go mod init go_webapp/helloworld

$go build

$./helloworld

$go run hello.go


---
$ sudo docker build -t go_webapp2:test .

$ sudo docker run -it -p 3031:3030 --name go_webapp2 go_webapp2:test

$ sudo docker container rm go_webapp2 -f