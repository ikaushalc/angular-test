Style Guide: Bootstrap
CSS Coding Standard: Followed by bootstrap
Installation instruction: Standard followed by angular-cli

# AngularProjectTestWithNgrx

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.2.

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



Description of how the application works: 
Datasource:
APIs
https://restcountries.eu/rest/v2/region/europe
https://restcountries.eu/rest/v2/region/asia

Application has 2 dropdown selection:
Step1: Choose the region from dropdown
Step2: Select the countries populated in the dropdown based selection in the region dropdown
Step3: Based on selection of the countries dropdown, following details are displayed:
1. Name
2. Capital
3. Population
4. Currency
5. Country Flag



Description of how application works:
The application is build using component model. The two main UI parts are area dropdown component and country-details component.
These component builds the UI layout using the parent app component. The structure of data/fields of interfaces are defined in
the models and state management using rxjs. The data is fetched from API using the countries service.



If you ran out of time what else you would have done:
Testing 
