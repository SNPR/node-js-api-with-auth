 ### Restful Api With Node.js with using Express &amp; MongoDB based on [this video](https://www.youtube.com/watch?v=2jqok-WgelI)
 
 Instruction:
 1. Clone repository.
 
 2. Install dependencies by command `yarn` or `npm i`.
 
 3. Install MongoDB and create database with name node_app_with_auth.
 
 4. Create in the project root directory ```.env``` file and past to it following code:
 
 ```DB_CONNECTION=mongodb://db_username:db_pass@db_adress:db_port/node_app_with_auth?retryWrites=true``` (also you can use cloud mongoDB);
 
 ```TOKEN_SECRET = RANDOM_NUMBERS_AND_LETTERS```
 
 5. `yarn start` or `npm start`.
