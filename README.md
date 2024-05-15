# BusManagementProject

Make sure to use # npm install command to install node modules
change this in package.json
"start": "react-scripts --openssl-legacy-provider start",

Attractive and responsive UI.
1. User can register and login.
2. User can search for bus, book the bus, add passengers, make payement and generate tickets.
3. A super user - Admin will be responsible for manipulating bus.
4. Interacts with API using Fetch API and Axios library
5. Additional feature to check weather for the present day and to email ticket
User can also check booking history
React-Router-DOM used for routing

Database Schema 
<img width="587" alt="Screenshot 2024-05-15 115312" src="https://github.com/suyashsk/BusManagementProject/assets/72683316/80f9114d-6472-4b6f-972b-867eb2b2d4fb">



How to Use/Control?
User can search for buss based on source, destination and date without logging in.
User can be directed to login/register using options from navbar
To book a bus user has to login.
For booking user has to enter passengers information.
User enter payment details for ticket generation.
User can either print the ticket.
How To Install.
Clone this project
Start by installing npm if you don't have it already.
run following commands :
npm install 
npm start or react-scripts start
Directory Structure
/src - all code files
/src/components - all react components
/src/services - service classes
/src/assests - css files, images and logos

Available Scripts
This project was bootstrapped with Create React App.

In the project directory, you can run:

yarn start or npm start
Runs the app in the development mode.
Open http://localhost:3000 to view it in the browser.
