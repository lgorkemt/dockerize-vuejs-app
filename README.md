# hello-world

- open the terminal

- check whether the vue is installed by typing vue in the terminal; vue 
(it should give you a list of help)

- if vue is installed you may create this application by; vue create hello-world

- check whether docker is installed by typing in the terminal; docker -v

- build an image with the command:

docker build -t vuejs-cookbook/dockerize-vuejs-app .

- run an instance of your image with the command:

docker run -it -p 8080:8080 --rm --name dockerize-vuejs-app-1 vuejs-cookbook/dockerize-vuejs-app

- check the docker instance is running with the command; docker ps

- Then go to localhost 8080 and see the app is Hello world! app is running


## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
