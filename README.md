Challenge 1: Settin' up a Basic Website with Docker
Goal:
Learnin' to use Docker to run a simple website locally.
Steps:

1. Prepare the Workspace:
   • Openin' yer computer and launchin' VSCode.
   • Create a new folder named "challenge1".
2. Addin' Content:
   • Inside "challenge1", create a folder called "public".
   • Put some funny pictures or files in the "public" folder.
3. Create Website File:
   • Inside "public", make a file called "index.html".
   • Write yer name and student ID in this file.
4. Makin' Dockerfile:
   • In "challenge1", make a file called "Dockerfile".
   • Write instructions in the Dockerfile to copy the content from the "public" folder to the Docker container.
5. Buildin' Docker Image:
   • Open a terminal in VSCode.
   • Use the terminal to build the Docker image from the Dockerfile.
6. Runnin' Docker Container:
   • After buildin', run a Docker container using the image you created.
   • Make sure to map a port (like 8080) from yer computer to the Docker container.
7. Checkin' Website:
   • Open a web browser and go to "http://localhost:8080".
   • Ye should see yer name and student ID on the website.
8. Commitin' and Pushin':
   • Use git to save yer changes.
   • Push yer code to GitHub or another remote repository.

---

Challenge 2: Creatin' a Dynamic Application with Docker Compose
Goal:
Learnin' to use Docker Compose to manage multiple Docker containers.
Steps:

1. Prepare the Workspace:
   • Open VSCode and create a new folder named "challenge2".
2. Addin' Files:
   • Extract the files from "challenge2.zip" and put 'em in the "challenge2" folder.
3. Makin' Dockerfile:
   • In "challenge2", create a file called "Dockerfile".
   • Write instructions in the Dockerfile to build the Node.js application.
4. Creatin' Docker Compose File:
   • Make a file called "docker-compose.yml" in "challenge2".
   • Write instructions in the YAML file to set up Nginx and the Node.js application.
5. Configurin' Nginx:
   • Create a file called "nginx.conf" in "challenge2".
   • Write instructions in the file to configure Nginx to listen on port 8080 and proxy requests to the Node.js application.
6. Startin' Services:
   • Open a terminal in VSCode and navigate to "challenge2".
   • Run the command docker-compose up to start the services defined in the Docker Compose file.
7. Checkin' Endpoints:
   • Open a web browser and visit "http://localhost:8080/api/books".
   • Make sure ye get a JSON response with book information.
8. Save Changes:
   • Use git to save yer changes.
   • Push yer code to GitHub or another remote repository.

Challenge 3:

1. Get Started:
   Download and extract challenge3.zip.
   Copy contents from previous Docker challenges into the challenge3 directory.
2. Environment Setup:
   Place the .env file with new user database passwords into the challenge3 folder.
3. Configure Docker Compose:
   Create or update docker-compose.yml in challenge3 with appropriate user database configurations from the .env file.
4. Running Docker:
   Start Docker Desktop.
   Execute docker-compose up -d to run containers in detached mode.
   Verify containers are running with docker-compose ps.
5. Build Images:
   Build Docker images using docker-compose build.
6. Test the Application:
   Navigate to http://localhost:8080/api/books to view the list of books in JSON format.
   Visit http://localhost:8080/api/books/1 for details on a specific book.
