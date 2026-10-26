# PlayApp

An Angular starter project generated with Angular CLI 19.2.9. It is a clean scaffold — the default app component and project wiring — with no app-specific features built on top of it yet.

## Tech stack

- Angular 19.2 + TypeScript, RxJS, Zone.js
- Angular CLI 19.2.9 for scaffolding, building and serving
- Karma + Jasmine for unit tests

## How to run

```bash
npm install
npm start        # ng serve — dev server at http://localhost:4200/
npm run build    # ng build — build artifacts go to dist/
npm run watch    # ng build --watch --configuration development
npm test         # ng test — Karma unit tests
```

## Code scaffolding

```bash
ng generate component component-name
ng generate --help   # list all schematics (components, directives, pipes, …)
```

## Project structure

```
src/main.ts       # Application bootstrap
src/app/         # Root app component (default scaffold)
src/index.html   # App shell
src/styles.css   # Global styles
public/          # Static assets
angular.json     # Angular workspace configuration
```

## Status

Starter only: a single initial commit. Build features on top of the default app component.
