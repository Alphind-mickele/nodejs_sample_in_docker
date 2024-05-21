build the image
docker build -t my-node-app .

run the container
docker run -d -p 3000:3000 --name my-node-container my-node-app
