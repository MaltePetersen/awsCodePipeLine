
# defaultNgConfiguration

This project is the default angular setup for my projects.
It is just the default Angular Application with some useful tools to
It supports multiple package which enable performance, bundle size optimization and documentation:
 - Augury Labs
 - Webpack Bundle Analyzer
 - Compodoc

## NPM Scripts
| name | use |
|--|--|
|ng  |starts angular cli|
|start |starts angular application|
|build |builds angular application|
|start:augury |start with augury performance analysis|
|test |runs test|
|lint |checks lint|
|e2e|runs e2e test|
|compodoc |generates documentation|
|build:stats |builds application with stats.json which analyze need to analyze the bundle|
|analyze|analyzes the bundle and opens a web page with the findings|


## Folder Structure
The folder structure is build after the Angular Style Guide.
.
├── angular.json
├── e2e
│   ├── protractor.conf.js
│   ├── src
│   │   ├── app.e2e-spec.ts
│   │   └── app.po.ts
│   └── tsconfig.e2e.json
├── package.json
├── package-lock.json
├── README.md
├── src
│   ├── app
│   │   ├── app.component.html
│   │   ├── app.component.scss
│   │   ├── app.component.spec.ts
│   │   ├── app.component.ts
│   │   ├── app.module.ts
│   │   ├── core
│   │   ├── feature
│   │   │   ├── firstChildComponent
│   │   │   ├── secondChildComponent
│   │   │   └── shared
│   │   └── shared
│   ├── assets
│   ├── browserslist
│   ├── environments
│   │   ├── environment.prod.ts
│   │   └── environment.ts
│   ├── favicon.ico
│   ├── index.html
│   ├── karma.conf.js
│   ├── main.augury.ts
│   ├── main.ts
│   ├── polyfills.ts
│   ├── styles.scss
│   ├── test.ts
│   ├── tsconfig.app.json
│   ├── tsconfig.spec.json
│   └── tslint.json
├── tsconfig.json
└── tslint.json

