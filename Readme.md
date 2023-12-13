My Website Instructions to build and run the website: 
Clone this repository.
Navigate to the directory containing the Dockerfile and index.html. 
Build the Docker container using the command:
``` docker build -t my-container .```
Run the container using:   
``` docker run -p 8090:80 my-container``` 
Access the website by visiting http://localhost:8090 in your web browser.
