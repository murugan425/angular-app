#Useful Commands to Deploy
STEP1: Create a Github Repo in the Git website (Ex:- RepoName: angular-app)
STEP2: Navigate to your project folder and follow the execute the below commands.
#Add the Origin in the Remote Repo.
STEP3: git remote add origin https://github.com/murugan425/angular-app
#Push the Remote to Master Branch 
STEP4: git push origin master
#Enable the Github Pages in Settings of Github.com.
#Install the angular-cli-pages Globally
STEP5: npm i -g angular-cli-ghpages
#Execute a build 
STEP6: ng build --prod --base-href='https://murugan425.github.io/angular-app/'
#Trigger the angular-cli-gh command
STEP7: Execute the command 'ngh'
#We can merge Step6 & 7 in a single command by adding a script in Package.json
"ghdeploy": "ng build --prod --base-href='https://murugan425.github.io/angular-app/' && ngh"
#Then Execute
npm run ghdeploy

# HelloAngular

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.4.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
