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
- 
## How to run?

Once you have all dependecies installed, to run the proyect execute the next command 

newman run PetStore.postman_collection.json -e Pet.postman_environment.json
