# Angular 2.x Predix UI Getting Started

This repository adds a minimal amount on top of the Angular CLI template to make things work with Predix UI. It
downgrades Angular to 2.4.x since all the Predix UI controls are still based on Polymer 1.0 and haven't been
upgraded to 2.0.  Further, the Angular 4.x / Polymer bridge only supported Polymer 2.0 or Hybrid 1.0/2.0 components
(of which Predix UI still is not).

This example also gives you a starting point on the CSS Design kit.  You can learn more about these on the 
Predix UI website https://www.predix-ui.com.

# Notes

I found that `webcomponents-lite.js` didn't produce the right results with IE11 and
Firefox for some reason. The `<px-card>` element was not laying out properly.
Including `webcomponents.js` instead produced more reliable results.

This example also includes `<px-kpi>` from the examples and it works fairly well.

## Angular CLI Guidance

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.3.0.

### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

### Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
