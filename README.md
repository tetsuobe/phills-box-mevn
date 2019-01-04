# Phill's BOX - Inventory app

| Docker components |
|-|
| Node |
| Mongo | 
| Mongo GUI |

| Stack |
|-|
| Vue |
| Babel |
| Cypress |
| Jest |
| PostCSS |

## Project setup

Copy `.env.dist` to `.env` and fill missing values.

```
docker-compose up
```
>It will fire up containers with Mongo and Node, and run command on a node conteiner

Application is avaliable on http://localhost:8080/

## Available node commands (for later usage)

### Install dependencies
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

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Run your end-to-end tests
```
npm run test:e2e
```

### Run your unit tests
```
npm run test:unit
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
