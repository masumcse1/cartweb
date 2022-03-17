# cartweb
servlet docker example 


http://localhost:8080/cartweb/HelloWorld

http://localhost:8080/CatWeb/HelloWorld




docker build -t myaps-web:1.0 .

docker run --name my-container -p 8080:8181 -t myaps-web:1.0
