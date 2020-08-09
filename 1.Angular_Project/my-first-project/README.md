Project name: my-first project

Intro: This project is my first project, which is a good practice for amateur front-end devlopers. It's  an Angular JS work. These Languages are included: JavaScript(.js/ .json), HTML, (.html), TypeScript(.ts) and CSS (.css) .


Step 1: I created the initial application structure using the Angular CLI. (CLI = Client). 
		I learned that the COMPONENTS display data.
		I used the double curly braces of interpolation to display the app title.


Step 2: I created a second component: Heroes
		I displayed this component by adding it to the AppComponent shell.
		I learned the two-way data binding with the ngModel directive, the AppModule and the importance of declaring components in the AppModule.

Step 3: I used *ngFor to display a list and *ngIf to conditionally include or exclude a block of HTML.
		I can toggle a CSS style class with a class binding.



Step 4: I created a reusable, seperate HeroDetailComponent and gave HeroesComponent parent control over the child 			HeroesDetailComponent with the help of property binding. 


Step 5: I created a new component: Messages.
		I learned how to create service for components: HeroService, MessagesServices


Step 6: I added the Angular router to navigate among different components.
		I turned the AppComponent into a navigation shell.
		I shared the HeroService among multiple components.


Step 7: I added the necessary dependencies to use HTTP in the app.
		I refactored HeroService to load heroes from a web API.
		I learned to configure an in-memory web API.
		I have updated the components to allow adding, editing, and deleting of heroes.
		I learned how to use observables.

		Check out: www.angular.io
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
