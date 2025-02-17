# BUS-APP

A bus ticket booking application built using the MERN stack (MongoDB, Express.js, React.js, Node.js).

The application includes the following features:

### Front-End

* Sign-In & Sign-Up pages.
* Token-based system ensuring only registered users can access the site using Passport.js.
* Password hashing with Passport.js.
* Profile page displaying user information.
* City selection for starting and destination points.
* List of buses from various companies with details.
* User-friendly seat selection page with dynamic forms for passenger data.
* Confirmation page collecting debit card data using react-credit-cards (payment process not included).
* Final page displaying ticket details and generating a random transaction ID.

### Back-End

* Backend built with Express.js.
* MongoDB Atlas for data storage.
* User authentication and token system with Passport.js.
* Password hashing before cloud storage using Passport.js.
* Dynamic seat data storage not supported in this version.

This project also demonstrates:

* A typical React project structure.

**Screenshots:**
Landing Page:

![](documentationResources/bus.gif)

Sign-In Page:

![](documentationResources/signin.png)

Bus Selection Page:

![](documentationResources/bus-page.png)

Seat Selection Page:

![](documentationResources/seatSelection.gif)

Payment & Confirmation Page:
![](documentationResources/payment.gif)

---

## Developed With

* [Visual Studio Code](https://code.visualstudio.com/) - A source code editor by Microsoft for Windows, Linux, and macOS.
* [Node.js](https://nodejs.org/en/) - JavaScript runtime.
* [React](https://reactjs.org/) - JavaScript library for building user interfaces.
* [Babel](https://babeljs.io/) - JavaScript transpiler.
* [Webpack](https://webpack.js.org/) - Module bundler.
* [SCSS](http://sass-lang.com/) - CSS metalanguage.
* [Bootstrap 4](https://getbootstrap.com/) - Open source toolkit for developing with HTML, CSS, and JS.
* [Axios](https://github.com/axios/axios) - Promise-based HTTP client for browser and Node.js.
* [Express.js](http://expressjs.com/) - Minimal and flexible Node.js web application framework.
* [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) - Global cloud database service.
* [Passport.js](http://www.passportjs.org/) - Authentication middleware for Node.js.

---

## Getting Started

Instructions to get a copy of the project running on your local machine for development and testing.

### Prerequisites

Ensure the following software is installed:

* Node 8.x
* Npm 3.x

Verify your node and npm versions with:

```bash
node -v
npm -v
```

### Install

Steps to set up the development environment:


* Install node modules:

  ```bash
  cd BUS_BOOKING_APP
  cd frontend
  npm install
  cd..
  cd backend
  npm install
  ```

### Starting the front-end and back-end servers

* Build the application:

  This command starts MongoDB and the front-end part.

  ```bash
  cd frontend
  npm start
  cd..
  cd backend
  npm run devStart
  ```

---
