# celerio-angular-quickstart

Using Celerio, reverse an existing database schema and generate an Angular/PrimeNG/Spring CRUD web application.

## Install dependencies

    cd src/main/webapp
    npm install

## Generate the app sources

From the root folder:

    mvn -Pdb,metadata,gen generate-sources

## Compile TypeScript files

    cd src/main/webapp
    npm run tsc

## Start the application

From the root folder:
    
    mvn spring-boot:run