# docker-devops

1) To build (while in project dir): 
`docker build -t my-node-app .`
To run with cpu and memory limitation: 
`docker run --cpus 0.5 --memory 512m -p 80:80 my-node-app`
    

2) Alternative (pulling from docker hub): 
 `docker pull katekn/my-node-app:latest`
Then run command provided above.
Site is available at http://localhost/
