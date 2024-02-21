

This project involves a gaming rental portal in which users can rent and buy games available. Front end of the application is done in HTML, CSS 3, Bootstrap 4, Semantic UI, JavaScript, Node.js, Express.js and EJS. For the backend MongoDB is used. Mongoose client is used to fetch the data from MongoDB. Login and Signup functionalities are validated using Express validator. Express sanitizer is used to sanitize the user inputs.

Used async and await method for retrieving data from MongoDB. This application also includes sessions to pass data from one page to another.

Suppose a user had logged in, all the games available to him except his games are shown in his profile. Suppose, no user has logged in, all the available games from the Database are shown. User can make swap requests to other available games.


app requires all these installations


npm install node
npm install express
npm install mongo
npm install nodemon
npm install http
npm install fs
npm install ejs
npm install express-session
npm install body-parser
npm install cookie-parser
npm install mongo-sanitize
npm install express-sanitizer
npm install mongoose
npm install async
npm install express-validator
