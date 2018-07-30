### July 30, 2018

# Angular.js
### step1:Setting up the development environment
    (node 8.x && npm 5.x)
#### Then install the Angular CLI globally.
    npm install -g @angular/cli

### step2:Create a new project
    ng new my-app

### step 3: Serve the application
    cd my-app
    ng serve --open
>   Using the --open (or just -o) option will automatically open your browser on http://localhost:4200/.
### step 4: Edit your first Angular component
>   src/app/app.component.ts

    export class AppComponent {
        title = 'My First Angular App!';
    }
    
>   src/app/app.component.css

    h1 {
      color: #369;
      font-family: Arial, Helvetica, sans-serif;
      font-size: 250%;
    }
