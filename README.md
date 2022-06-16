# Postman Challenge Perficient QA Bootcamp

Here you have the response to an Api test, performed in Postman and the following  Api https://petstore.swagger.io/#/ 

## What was tested?

- Add pet ( POST).
- Get Pet (GET).
- Place an order for a pet (POST).
- Get the order plced (GET).

## Install Dependencies

- Node js
- npm install -g newman
- npm install -g newman-reporter-htmlextra

## How to run?

Once you have all dependecies installed, to run the project execute the next command 

```
newman run PetStore.postman_collection.json -e Pet.postman_environment.json
```

## HTML Report

If you prefer, execute the next command to see the report in a Html format insted of the console.
Then, open the generated file and view the report in your browser. 

```
newman run PetStore.postman_collection.json -e Pet.postman_environment.json -r htmlextra
```
