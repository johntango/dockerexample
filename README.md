# dockerexample
Build the Docker image by running
docker build -t myImage .
The run the image in a container using
docker run -p 3000:3000 myImage

In your browser now type
localhost:3000/random 
you should see a different colored page every time you refresh the page
