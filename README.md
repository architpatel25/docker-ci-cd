
# Create Automated CI/CD Builds Using GitHub Actions and DockerHub.

### 1 : Create Sample NodeJS Application 
### 2 : Install Docker into local system and run docker image with docker compose
### 3 : Create a Docker Hub account
### 4 : Upload image into DockerHub with Tag.
### 5 : Upload codebase into Github.
### 6 : Add Dockerhub token + Github Username into secret keys into github account
### 7 : Create a workflow for the same and paste your github username with dockerhub token - given in file(main.yml)

## Usage

You can use this Docker image directly in demos or use it as a simple [Node.js app](#nodejs-app)

### Node.js App

Start the app

```bash {"id":"01HQQJQVVQQPXMPB6VQ59JQ70B"}
npm start
```
We also also use [nodemon](https://nodemon.io/) to automatically restart the app when code changes. Use the `dev` command to put everything together

``` and then open [http://localhost:3000](http://localhost:3000) in your browser. ```

### Docker Image

```sh {"id":"01HQQJQVVQQPXMPB6VQ0YMFN5B"}
docker build . -t docker-demo #DOCKER_IMAGENAME
docker run -p 3000:3000 docker-demo
```
### Install and Run Docker Image

``` https://docs.docker.com/get-started/03_updating_app/ ```

### Upload Docker Image into DockerHub Account 

``` https://docs.docker.com/get-started/04_sharing_app/ ```

### Finally, Run your application in your local system with port(3000)

![Hey-Archit](https://github.com/architpatel25/docker-ci-cd/assets/25317936/4065f3b7-273b-40d5-85ca-c0cee1e0e123)

