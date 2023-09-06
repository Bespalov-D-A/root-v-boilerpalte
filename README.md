## Root-v-boilerplate
###  Nginx

This template is perfect for sharing with [React-v-boilerpalte](https://github.com/Bespalov-D-A/React-v-boilerplate) and [NestJS-v-boilerpalte](https://github.com/Bespalov-D-A/NestJS-v-boilerplate).
#####  Using
- Clone the current repository
- Rename the .example.env file to .env
- create a 'client' folder and deploy the contents of [React-v-boilerpalte](https://github.com/Bespalov-D-A/React-v-boilerplate) there,
- create a 'server' folder and deploy the contents of [NestJS-v-boilerpalte](https://github.com/Bespalov-D-A/NestJS-v-boilerplate) there. 
- The final structure should be like this:  
THIS_REPOSITORY/server/  
THIS_REPOSITORY/client/  
 - Go to the 'client' folder and run ```npm i```
 Rename the .example.env file to .env
 - Go to the 'server' folder and run ```npm i```
 Rename the .example.env file to .env
The values for POSTGRES_DB, POSTGRES_USER, and POSTGRES_PASSWORD should match the values from .env in root-v-boilerplate
 - Execute the command ```docker-compose build```
 - Launch the application using ```docker-compose up```
  
#####  Info
 - Your client should be accessible at: http://localhost:80
 - Your server should be accessible at http://localhost:80/api for browser access (e.g., from React) and http://localhost:5000 for general access.
- Your adminer for database management will be accessible at: http://localhost:5001

Author: [Bespalov.D.A.](https://github.com/Bespalov-D-A)
