Delete this readme and node modules with json packages (if needed) but must delete redme
clone repo
run:  npm init -y
run: npm install express

#build the image
docker build -t my-web-app .

#run the docker container
docker run -p 3000:3000 my-web-app

#verify
docker images

