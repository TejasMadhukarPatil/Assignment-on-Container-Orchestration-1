# Assignment-on-Container-Orchestration-1
Develop Kubernetes deployment files for both frontend and backend components, ensuring seamless deployment and scalability.  Create a HELM chart to streamline the deployment process, allowing for easy configuration and management.  Write Jenkins Groovy code to automate the build deployment process, ensuring consistency or efficiency CI/CD pipeline.

Installing the node_modules:



npm install --force
Create .env file with following content but change the link to backend:



REACT_APP_API_BASE_URL=http://localhost:3001



Build Steps
Building the docker image. React application is running at port 3000 inside the container and is exposed at port 80 in host machine.



docker build -f Dockerfile -t frontend-lrccapstone .
docker run -it -p 80:3000 frontend-lrccapstone

backend


Nodejs, mongodb
