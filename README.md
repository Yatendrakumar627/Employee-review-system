# Issue-Tracker
# Employee review system

This Employee review web application is created for employees to submit feedback toward each other's performance. User's could have either "employee" or "admin" role. There are two dashboard pages based on the role of the employee those dashboard pages will be rendered, User with role of admin can assign employees to participate in review of other employees. Employees can only submit feedback required by assigned reviews. \
It is built using NodeJs, ExpressJs, MongoDB, EJS and JavaScript.

### 🔗 Hosted link: [Employee review system]
(https://employee-review-system-swdp.onrender.com)

![](./public/Screenshot%20(3136).png)

## ⚙️ Functionality

### Admin's functions

- Add employee
- Delete employee
- Update employee details
- Assign review to employee
- Update review of employee

### Employee's functions

- Submit reviews assigned to it
- View reviews given by others

## 🧑‍💻 Getting started

- Fork the project
- Clone the forked repository in your local system
- Create .env file in the root directory and add the following:-
  - PORT="Your port number"
  - MONGODB_URL="Your MongoDB URL"
  - SESSION_SECRET_KEY="Your secret session key"
- Install all required packages

```bash
npm install
```

- Run project

```bash
npm start or nodemon index.js
```

The project is running on the port number provided by you.

## 🛠️ Tools Used

- NodeJS
- MongoDB
- ExpressJS
- EJS
- Mongoose

### 📚 Libraries:

- bcryptjs
- connect-flash
- connect-mongo
- cookie-parser
- dotenv
- ejs
- express
- express-ejs-layout
- express-session
- mongoose
- passport
- passport-jwt
- passport-local

## 🖼️ Screenshots

![](./public/Screenshot%20(3137).png)
![](./public/Screenshot%20(3139).png)
![](./public/Screenshot%20(3143).png)
![](./public/Screenshot%20(3144).png)
![](./public/Screenshot%20(3145).png)
![](./public/Screenshot%20(3147).png)
![](./public/Screenshot%20(3148).png)
