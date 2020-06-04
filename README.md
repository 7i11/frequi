# frequi

Freqtrade UI build with [Vue.js](https://vuejs.org/) and [boostrap-vue](https://bootstrap-vue.org/).

## WARNING

This project is still in it's early stages (consider it early-alpha), and is not yet stable nor recommended to be used for production usages.

It will require Freqtrade to be running on the same host with the API enabled under (`localhost:8081`). This port can be changed in `vue.config.js`.


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

### Build and run docker version

```
docker-compose build
docker-compose up -d

# Access using http://localhost:8080/
```


### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
