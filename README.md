# MDN_Local_Library

- My initial Node/Express project: 'Local Library' website!
- This web application creates an online catalog for a small local library, where users can browse available books and manage their accounts.
- Live demo : https://mdn-local-library.onrender.com

## UML Diagram
A UML diagram showing the relation of local library database entities hosted on MongoDB Atlas.
![A UML diagram showing the relation of database entities in this example repository](https://raw.githubusercontent.com/mdn/express-locallibrary-tutorial/main/public/images/Library%20Website%20-%20Mongoose_Express.png)

## Quick Start

To get this project up and running locally on your computer:

1. Set up a [Node.js](https://wiki.developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/development_environment) development environment.
2. Once you have node setup install the project in the root of your clone of this repo:

   ```bash
   npm install
   ```
3. Run the server, using the command line shell for your environment:

   ```bash
   # Linux terminal
   DEBUG=express-locallibrary-tutorial:* npm run devstart
   
   # Windows Powershell
   $ENV:DEBUG = "express-locallibrary-tutorial:*"; npm start
   ```
4. Open a browser to <http://localhost:3000/> to open the local library site.