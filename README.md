# Gralette 
La roulette du gras

## Stack technique
- Vite
- Vue 
- Vitest

## Note 
Vous pouvez retiré la partie docker de chaque commande si vous ne souhaitez pas utiliser docker.

## Project Setup

```sh
docker compose run --rm node npm install
```

### Compile and Hot-Reload for Development

```sh
docker compose up
```

### Compile and Minify for Production

```sh
docker compose run --rm node npm run build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
docker compose run --rm node npm run test
```


### Lint with [ESLint](https://eslint.org/)

```sh
docker compose run --rm node npm run lint
```
