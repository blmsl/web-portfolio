## Web Portfolio source code

### build & run
`npm install -g @angular/cli`
`npm install`
`ng serve`

### deploy ng project to github page
`ng build --prod --output-path docs --base-href web-portfolio`

https://github.com/angular/angular-cli/wiki/stories-github-pages

### deploy on firebase host
```
firebase login
firebase init
ng build --prod
firebase deploy
```

### angular clean project files
```
../
angular-cli.json - angular CLI config
karma.conf.js - Karma is test runner
protractor.conf.js - Protractor is end to end (2t2) testing framework
tsconfig.json - TypeScript lang compiler config
tslint.json - for TypeScript linting (analyse code for errors)
```

```
../src/
main.ts - entry point of app
polyfills.ts - polyfills to run an Angular app in most browsers 
test.ts - main point for unit tests
tsconfig.app.json - TypeScript compiler configuration
tsconfig.spec.json  - TypeScript compiler configuration.
typing.d.ts - TypesScript declaration files
```