# WebTestKit

This project is a web application built using Node.js and the Express.js framework. The application implements core user authentication and authorization features and includes static pages for different user roles.

## Getting Started

After cloning the repository from GitHub to your local machine, install the project dependencies:

```
npm install

```


To start the application:

```
npm start

```
Or

```
node index.js

```

The application will be accessible at http://localhost:3000 in your web browser.


## Functionality

- Handling user authentication on the /login page using sessions.
- Server-side session storage using express-session.
- Inbound and outbound redirects on pages.
- Implementation of /public, /login, and /protected pages with corresponding static HTML files.
- Use of EJS templates for rendering pages.


## Dependencies

- body-parser: ^1.20.2
- ejs: ^3.1.9
- express: ^4.18.2
- express-session: ^1.17.3
- jsonwebtoken: ^9.0.2
- nodemon: ^3.0.1
- store: ^2.0.12
