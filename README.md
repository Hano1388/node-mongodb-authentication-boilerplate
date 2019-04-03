# Node MongoDB Authentication Boilerplate

This is a part of another project that serves to handle signin, signup, and authenticate users.

### Installation
*Inside the project directory run the following two commands:*
```
npm install
npm start
```

### Used Resource
- [bcrypt-nodejs](https://www.npmjs.com/package/bcrypt-nodejs): to generate a salt and encrypt user password with it
- [jwt-simple](https://www.npmjs.com/package/jwt-simple): to generate a token for user
- [mongoose (ODM)](https://mongoosejs.com/): to deal with mongoDB
- [passport](http://www.passportjs.org/) & [passport-jwt](https://www.npmjs.com/package/passport-jwt): to handle user authentication
- [passport-local](http://www.passportjs.org/packages/passport-local/) to handle login
