# Adminpro

## Estructura de Directorios

Para proyectos pequeños dentro de la carpeta `app` podemos tener:

- Componentes
- Servicios/Providers
- Guards/Protectores
- Directivas

Para proyectos grandes apuntaremos a esto:

```
app
   |_404      -> cualquier ruta que no exista se dirige aca
   |_login    -> login y registro
   |_pages    -> paginas o pantallas de la app
   |_shared   -> componentes compartidos por la app(menus)
   |_signup

```

Dentro de la carpeta `pages` podemos tener algo como:

```
pages
    |_ component    -> componentes personalizados
    |_ form
    |_ icons
    |_ starter
    |_ table        -> paginas de tareas especificas
    pages-routing.module.ts  ->subrutas
    pages.component.html
    pages.component.spec.ts
    pages.component.ts
    pages.module.ts -> modulo propio para empaquetar archivos
```

## Uso del template administrativo

## Código fuente del template

## Uso de librerías externas

## Creación de los primeros componentes

## Separar el Login del template administrativo, ya que tienen estructuras diferentes

## Animaciones por CSS

## Respaldos en GitHub


# Angular

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.2.1.

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
