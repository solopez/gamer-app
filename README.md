# Monorepo
# Angular & NestJS web apps + libraries with NX


# Cart app

## Demo
https://gamer-app-api.herokuapp.com/

## Storybook
https://solopez.github.io/monorepo

## Local serving
npm run serve-all (will serve api + web app both)

npm run storybook

### Serve individually:

Front: nx serve games 

Back: nx serve games-api

## Testing
npm run test (will run all)
### Jasmine
nx test games-product-detail

nx test games-product-list

nx test games-search

### Jest

nx test games-api

## Angular Universal - Server Side Rendering
npm run build:ssr

npm run prerender
