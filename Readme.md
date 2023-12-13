# My Website\n\nInstructions to build and run the website:\n\n1. Clone this repository.\n2. Navigate to the directory containing the Dockerfile and index.html.\n3. Build the Docker container using the command:\n   ```
   docker build -t my-container .
   ```\n4. Run the container using:\n   ```
   docker run -p 8090:80 my-container
   ```\n5. Access the website by visiting http://localhost:8090 in your web browser.

