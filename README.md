angular :- 
1. created the project

2. create the component 
    a. register component

3. created the service 
    a. jwt

4. added the routing 
   a. register component in the app-routing.module.ts

5. added the import
   a. HTTPClient import in the app.module.ts;

6. added a nav bar in the appcomponent.html

7. Jwt service
   a. injected the HtppClient object in the constructor
   b. provided the backend BASE_URL;
   c. created the register method

8. made form for the register compnonent
  a.  in the registerComponent.html
  b. added css in the registerComponent.scss

9. ab hume iss form ko bind karna hai , apne registerComponent.ts file se
   or waha se get karke hume  jwtservice ko dena hai , or ye service form ke data ko backend mein bhej degi

so to do this 

10. we need to add import in our appModule.ts
    a. import ReactiveFormsModule

11. made the several method in the registerComponent.ts file


12. create the login component
13. add import of loginComponent  in the app routing module.ts
14. create a login method in the jwtService.ts
15. made a form for the login component and added css for that form
16. ab iss form ki implementation denge login component.ts

Same for dashboard
create dashboard component and rest of the steps are same




















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
