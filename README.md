# Medium React Docker Optimization


### Start React app

All commands need to be run inside `./my-app/` folder:

Install dependencies
```sh
yarn install
```

Start local development server (Chrome tab is automatically opened on http://localhost:3000/)
```sh
yarn start
```

### Docker
Build Docker image
```sh
docker build -t react-nginx .
```


Start Docker container

```sh
docker run -d -p 8080:80 react-nginx
```


// toturial link on Meduim
https://faun.pub/decreasing-your-node-js-docker-image-size-by-90-84cc1b1093d9
https://medium.com/swlh/how-we-reduced-react-docker-image-by-17x-cd684898470f
