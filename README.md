Delete this readme (after cloning)
clone repo
navigate to direcory
run:  npm init -y
run: npm install express

#build the image
docker build -t my-web-app .

#run the docker container
docker run -p 3000:3000 my-web-app

#verify
docker images

