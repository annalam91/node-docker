This repositroy is a basic boilerplate just using node and docker.

## Run this appliction using node.

You would need to run the following commands:

`npm install`

`node app.js`

Then visit in your browser http;//localhost:8080 to see it up and running.

## Run this application using docker.

To run this within a docker container you would need to run:

`docker build -t <docker-image-name> <filepath>`


I used this command which you can copy and use

`docker build -t node-test .`


Then run

`docker image ls` 

This will let you know if the image has been built successfully.
Once you can see it running successfully you can then run the docker iamge using this command:

`docker run -d -p 8080:8080 node-test`

Then you can run the following command to see your container running.

`docker ps -a` 

