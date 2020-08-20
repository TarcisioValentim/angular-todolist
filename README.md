# AngularTodolist

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.0.5.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## steps
// add (apikey) que esta na URL: www.console.firebase > no campo >>seus aplicativos >> cdn.
// agora instale as dependencias do firebase via Bash, com o comando: 
                    npm i @angular/fire.
// now cd src/app/app.module.ts >> importe as duas linhas:
    >import { AngularFireModule } from 'angularfire2';
    >import { AngularFireDatabaseModule } from 'angularfire2/database';
// now src/index.html >> add <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
//now create component with comand: 
                    ng g c todo
//dependencias add:
                    ng add @angular/fire

                    npm install firebase@latest
//iniciar servidor:
                    ng serve. //localhost:4200

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
