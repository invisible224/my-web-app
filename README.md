install nodejs if not installed
# create a directory name:  my-web-app
navigate to directory: cd my-web-app (run all commands inside this directory)

Open CMD 
  run:  npm init -y  
  run: npm install express
  copy the  index.js and Dockerfile in the directory 

(all on CMD)
run: docker login
#build the image:
  docker build -t my-web-app .

#run the docker container: (optional)
  docker run -p 3000:3000 my-web-app

#verify the  image
  docker images

