Create a docker compose file to have two hello-world container, one will display hello-world1 another will show hello-world2. Add another load-balancer, so that whenever we point to http://localhost, first will display hello-world1, another will show hellp-world2


#How to create myapp image:

1. Clone a docker examples repo by running: git clone https://github.com/docker/awesome-compose.git. 
2. cd awesome-compose/flask
3. Inside the flask directory, run: docker build -t myapp app/. 

