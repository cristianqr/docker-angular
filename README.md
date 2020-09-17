# Docker Angular
This project show how to create a docker image based on Dockerfile

## Process to test
1. Clone the repository: `git clone https://github.com/cristianqr/docker-angular.git`
2. Open the project directory
3. Create docker image: `docker build -t docker-angular .`
4. Run docker container: `docker run -it -p 80:80/tcp --name angular-app docker-angular`
5. On the browser get into: http://localhost:80/
