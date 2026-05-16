# SnakeGame

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.0.3.

# Running

## Requirements

Node.js version 20 or higher

## 1. Start API server <small>(inside `games-server` folder)</small>

### Navigate to the `games-server` folder

```bash
cd games-server
```

### Installation

```bash
npm install
```

### Start server

```bash
npm run start
```

You can optionally provide port the server should listen at with additional param
`post:{{port_number}}`

Example:

```bash
npm run start port:8080
```

### Available pages

When server is running then you have access to:

- High scores page:  
  http://localhost:8080/snake

- **API** documentation page:  
  http://localhost:8080/docs

## 2. Start Angular application <small>(inside project root folder)</small>

### Installation

```bash
npm install
```

### Run application

```bash
npm start
```

### Application URL

http://localhost:4200

# Angular CLI Reference

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
