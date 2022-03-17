# cartweb
servlet docker example 


http://localhost:8080/CatWeb/HelloWorld


------------------------

docker build -t myaps-web:1.0 .

docker container run -it -d --name tomcatcontainer1 -p 8080:8080 myaps-web:1.0
-----------------------------------------------------------------------------------
no work : docker run --name my-container -p 8080:8181 -t myaps-web:1.0
