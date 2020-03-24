# Communique

This is a messaging app created to lean about Angular and TypeScirpt. Some of the features include: user authentication, authorization, and pagination.

## Screenshot

### Before Signup

Prior to signing up users can view all messages.

!["Prior to signing up users can view all messages"](https://github.com/Lizzyfemme/communique/blob/master/screenshots/prior-to-signup.png)

### Signup and Login Page

New users can signup for Communiqué, and existing users can login.

!["Signup and login page"](https://github.com/Lizzyfemme/communique/blob/master/screenshots/singup_and_login.png)

### User's View

Once logged in users can edit and delete their own posts, but not the post of other users.

!["Edit and Delete buttons visable on posts"](https://github.com/Lizzyfemme/communique/blob/master/screenshots/user_view.png)

### Error Messages

An error message will occur if a user makes a mistakes, or uses Communiqué incorrectly.

!["Error Message popup"](https://github.com/Lizzyfemme/communique/blob/master/screenshots/error.png)

## Stack

- MongoDB
- Angular
- NodeJS
- Express
- Angular Material
- Mongoose
- mongoose-unique-validator
- bcrypt
- jsonwebtoken
- Multer

## Getting started

1. Fork or clone the repo.
2. Run `npm install` to install all dependencies.
3. Create a MongoDB sandbox.
4. Add the login information to the backend/app.js file.
5. Run `ng serve` to start the Angular server.
6. Run `npm run start:server` to start the express server.

## Other options

### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

Start the express server by running `npm run start:server`

### Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.
