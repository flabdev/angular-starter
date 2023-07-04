![81993396-d5142b00-9645-11ea-995f-98342b7d5c8f](https://user-images.githubusercontent.com/7531596/128626297-df86020b-1cdc-43b5-a692-6c4c45534ec1.png)

> The Angular starter kit to start a new enterprise project. Contains below list of libraries

✅ [Angular 16](https://angular.io/)  
✅ [Angular Material](https://material.angular.io/)  
✅ Unit Testing with [Jest](https://jestjs.io/)  
✅ End-to-End Testing with [TestCafé](https://testcafe.io/)  
✅ Internationalization with [Transloco](https://github.com/ngneat/transloco)  
✅ Auto documentation with [Compodoc](https://compodoc.app/)  
✅ Provide component examples with [Storybook](https://storybook.js.org/)  
✅ Analyse your project with [source-map-explorer](https://www.npmjs.com/package/source-map-explorer)  
✅ [Docker](https://www.docker.com/)  
✅ [ESLint](https://eslint.org/)  
✅ [Prettier](https://prettier.io/)  
✅ [Commit Linting](https://github.com/conventional-changelog/commitlint)  
✅ [AuditJS](https://www.npmjs.com/package/auditjs) Audit this application using Sonatype OSS Index  
✅ Auto-generate a CHANGELOG with [auto-changelog](https://github.com/cookpete/auto-changelog)

<hr>

## Prerequsites
node (please install node in your machine to continue.)
Git


## Install / Development

```bash
# Clone the project
$ git clone https://github.com/flabdev/angular-starter
$ cd angular-starter

# Install dependencies
$ npm install

# Start server
$ npm run start

# Open in browser: http://localhost:4200
```

## Docker Deployment

```bash
# Build Docker image
$ docker build . -t angular-starter

# Run Docker Container
$ docker run -p 3000:80 angular-starter
```



## Commands

- `npm run start` - Start the app
- `npm run lint` - Lint the project
- `npm run test` - Run unit tests
- `npm run build` - Build the project
- `npm run build:prod` - Build the project in production mode
- `npm run build:prod:stats` - Build the project in production mode with stats
- `npm run analyse` - Analyse bundle with [webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer)
- `npm run compodoc` - Generate [compodoc](https://github.com/compodoc/compodoc) documentation
- `npm run version` - Generate changelog
- `npm run prettier` - Format the whole project
- `npm run audit` - Audit this application using Sonatype OSS Index


