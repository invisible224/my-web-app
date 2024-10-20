install nodejs if not installed
# create a directory name:  my-web-app
navigate to directory
run:  npm init -y  \n
run: npm install express

#build the image:\n
docker build -t my-web-app .

#run the docker container: \n
docker run -p 3000:3000 my-web-app

#verify
docker images

