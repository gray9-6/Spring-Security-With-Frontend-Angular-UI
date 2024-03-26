Created the Angular project.

Created a component:
a. RegisterComponent.

Created a service:
a. JwtService.

Added routing:
a. Registered the RegisterComponent in the app-routing.module.ts.

Added imports:
a. Imported HttpClientModule in the app.module.ts.

Added a navigation bar in the app.component.html.

JwtService:
a. Injected the HttpClient object in the constructor.
b. Provided the backend BASE_URL.
c. Created the register method.

Created a form for the RegisterComponent:
a. Implemented in the registerComponent.html.
b. Added CSS in the registerComponent.scss.

Now, we need to bind this form and pass it to the JwtService from the registerComponent.ts file.

To do this, we need to add imports in our appModule.ts:
a. Imported ReactiveFormsModule.

Implemented several methods in the registerComponent.ts file.

Created the LoginComponent.

Added import of LoginComponent in the app-routing.module.ts.

Created a login method in the JwtService.ts.

Created a form for the LoginComponent and added CSS for that form.

Implemented the form in the loginComponent.ts.

Same process for the Dashboard:

Created Dashboard component.
Rest of the steps are the same.




















# JwtAngular

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.2.13.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
# Spring-Security-With-Frontend-Angular-UI
