# Login APP

UI example can be found here:
https://codepen.io/ricardoolivaalonso/full/YzyaRPN

## Task

- Create **Login Page** (/login)
    - username/email input
    - password input
    - submit button
- Create **Register Page**
    - username/email input
    - password input
    - repeat password
    - submit button
- Create **Reset Password Page**
    - username/email input
    - submit button
- Create **Home Page** for Logged In Users
    - show the name of application (choose the one you'd like)
    - some hello words
    - header on the top, with 1 link to settings page and small icon LOGOUT
    - on click on settings we should redirect user to the settings page
    - on click on logout we should logout user and redirect him to login page
- Create **Settings page**
    - Header title: Settings Page
    - User info:
        - display username
        - LOGOUT button

## Additionally

- Implement login through the social media buttons:
  - Add social media button to the Login Page
  - On click redirect to the action, that will get user data and save it to the application storage

**Use cases, that should be covered:**

- When user is not logged in, when he enters a route he cannot enter (like settings page or home), he will be redirected to /login page

**Requirements**

- Create this small application using **JS/HTML/CSS**
- Use window **localStorage/sessionStorage** to save user data and verify that user logged in/out
- Use window **history** to redirect user to different pages (you can use hashes instead of routes)
- Add at lest some unit test using Jest

Application repo should have next scripts, in order to check how it works:

`lint` (using eslint) <br />
`build` (a build version) <br />
`start` (to run application locally using webpack static server) - this should start the FE webpack to rebuild app on changes + this should start a backend NODEJS server <br />

### Which technologies will be covered in this task:

* Webpack
* Jest
* Eslint
* JS/HTML/CSS
* window objects like: history and localStorage/sessionStorage
