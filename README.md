
# Docker CI/CD

## Usage

You can use this Docker image directly in demos or use it as a simple [Node.js app](#nodejs-app)

### Docker Image

```sh {"id":"01HQQJQVVQQPXMPB6VQ0YMFN5B"}
docker build . -t docker-demo #DOCKER_IMAGENAME
docker run -p 3000:3000 docker-demo
```

### Node.js App

Start the app

```bash {"id":"01HQQJQVVQQPXMPB6VQ59JQ70B"}
npm start
```

and then open [http://localhost:3000](http://localhost:3000) in your browser.

### Local Development

```sh {"id":"01HQQJQVVQQPXMPB6VQ85M8PVC"}
npm install 
```

We also also use [nodemon](https://nodemon.io/) to automatically restart the app when code changes. Use the `dev` command to put everything together

```sh {"id":"01HQQJQVVQQPXMPB6VQ97PQ6QA"}
npm run dev
