## Root-v-boilerplate
###  Nginx

This template is perfect for sharing with [React-v-boilerpalte](https://github.com/Bespalov-D-A/root-v-boilerpalte) and [NestJS-v-boilerplate](https://github.com/Bespalov-D-A/root-v-boilerpalte).
This template is ideal for use with root-v-boilerpalte, although you can use it separately.
If you are using a combination with React-V-Boilerpalte, read [HERE](https://github.com/Bespalov-D-A/root-v-boilerpalte)
 how to combine these Boilerpaltes.
#####  Using
- Clone the current repository,
- create a 'client' folder and deploy the contents of [React-v-boilerpalte](https://github.com/Bespalov-D-A/React-v-boilerplate) there,
- create a 'server' folder and deploy the contents of [NestJS-v-boilerpalte](https://github.com/Bespalov-D-A/NestJS-v-boilerplate) there.
- The final structure should be like this:
THIS_REPOSITORY/server/
THIS_REPOSITORY/client/
 - Go to the 'client' folder and run ```npm i```
 - Go to the 'server' folder and run ```npm i```
 - Execute the command ```docker-compose build```
 - Launch the application using ```docker-compose up```
  
#####  Info
 - Your client should be accessible at: http://localhost:80
 - Your server should be accessible at http://localhost:80/api for browser access (e.g., from React) and http://localhost:5000 for general access.
- Your adminer for database management will be accessible at: http://localhost:5001

Author: [Bespalov.D.A.](https://github.com/Bespalov-D-A)
