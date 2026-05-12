# SnakeGame

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.0.3.

# Running application

Install game-server: `npm install - inside the game-server folder`

Run game-server: `npm run start - inside the game-server folder`

- you can optionally provide port the server should listen at with additional param `post:{{port_number}}`
  example:
  `npm run start port:8080`

Run the main application: `npm install / ng serve`

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Game server

When server is running then you have access to:

- High scores page:
  http://localhost:8080/snake

- **Api** documentation page  
  http://localhost:8080/docs

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
