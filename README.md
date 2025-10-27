This application is a basic node.js project using express for learning docker
How to build and run the container
To build it we've used the command:  docker build -t node-docker:latest .
And to run it we've used : docker run -p 3000:3000 --name node-docker -dev -v $(pwd)/node-docker:/app -v /app/node_modules myapp:latest
