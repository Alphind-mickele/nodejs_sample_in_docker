sudo yum update

sudo yum install docker

sudo service docker start


sudo chkconfig docker on


sudo usermod -aG docker ec2-user


docker --version


#Build the image

docker build -t my-node-app .

#Run the container

docker run -d -p 3000:3000 --name my-node-container my-node-app
