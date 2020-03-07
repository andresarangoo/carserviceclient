# CarServiceClient

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.1.2.

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

## Para listar owners

Se crea el componente owner-list, en el html se hace el estilo para listar los datos, en el ts se realizan los metodos para guardar y eliminar owner.

## Para eliminar

Luego de tener la lista de owners, se agrega un select list para seleccionar no o más owners y asi eliminarlos. En el ts esta el método para elinar tanto el owner como la relación entre owner y car.

## Para editar y agregar owners

Se crea el componente owner-edit, en este  se piden los datos de nombre, dni y profesión. En caso de No querer agregarsolo se da cancelar y se regresa a owner-list.
Para editar, en el owner-list se seleccciona un owner y se procede a cambiar lo necesario, en caso de querer agregar, click en el boton agregar y con este se accede al formulario para agregar.

## Agregar owner a car

Al momento de crear o modificar un car, se crea un innput para agragar el owner.

## Agregar routing

Se agregan las rutas necesarias al app-routing para asi poder aceder a las diferentes vistas.

## Agregar Service

Se crea el Service para owner con el cual podemos acceder a la base de datos y hacer los métodos del CRUD.