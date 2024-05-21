docker build -t my-node-app .
docker run -d -p 3000:3000 --name my-node-container my-node-app
