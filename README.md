# Angular CRUD
Basic Angular app with Create-Read-Update-Delete functionalities.

### Initiate the project
Run in the terminal:
    ```shell
    ng new angular-crud
    ```

### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

### Running JSON-SERVER

Run `json-server --watch db.json`. Navigate to `http://localhost:3000/employees` or whatever localhost provided in the terminal.

### Material Angular

Visit the link for the docs: [https://material.angular.io/components/categories](https://material.angular.io/components/categories)
1. Install package:
    ```shell
    ng add @angular/material
    ```

### JSON SERVER

Visit the website to see the docs: [https://www.npmjs.com/package/json-server](https://www.npmjs.com/package/json-server)
1. Install the package:
    ```shell
    npm i json-server
    ```
1. Running the server:
    ```shell
    json-server --watch db.json
    ```

### Create the components
1. Create the Dialog component
    ```shell
    ng g c emp-add-edit
    ```
1. Create a new folder under app and name it `services` then create the employee service.
    ```shell
    ng g s services/employee
    ```
1. Create a new folder under app and name it `core` then create the core service.
    ```shell
    ng g s core/core
    ```