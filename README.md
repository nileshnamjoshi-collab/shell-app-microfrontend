# AngularAppOfApps

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

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

## Create main app

Run `ng new my-app --routing`

## Create your Sub Applications

When I created the initial prototype, I used the Nrwl Extensions for Angular because they had a feature to support multiple applications in the same workspace. However, the multiple application functionality is now baked directly into the Angular CLI so this post will focus on that. Instead of using ng new to create the workspace, we want to use `ng generate application`. This will create a new application, residing right next to the default application:
`ng generate application app1 –-routing`
`ng generate application app2 –-routing`

## Refer url

`https://medium.com/disney-streaming/combining-multiple-angular-applications-into-a-single-one-e87d530d6527`
