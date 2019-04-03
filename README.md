# Node MongoDB Authentication Boilerplate

This is a part of another project that serves to handle signin, signup, and authenticate users.

### Installation
*Inside the project directory run the following two commands:*
```
npm install
npm start
```

### Used Resource
- bcrypt-nodejs: to generate a salt and encrypt user password with it
- jwt-simple: to generate a token for user
- mongoose (ORM): to deal with mongoDB
- passport & passport-jwt: to handle user authentication
- passport-local to handle login
