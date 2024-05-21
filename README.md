Build the image

docker build -t my-node-app .

Run the container

docker run -d -p 3000:3000 --name my-node-container my-node-app
