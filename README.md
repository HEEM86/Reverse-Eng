# Reverse-Engineer Applicatin README


## Description

The assignment is based on reviewing code and providing content that explains the functionality with a summary of how the files execute the application. 


## Tech Used
- Javascript
- HTML
- CSS
- node
- MVC

## Overview and Summary

**Overview**

This application is a optin for a membership, which  has input values for the user to enter their email and password to login.

**Summary**

JS Folder: Starts to application
The application begins in the js folder with the signup, members and login js files. These folders take in the values of a new user trying to register or an existing user loggin in. So, the user chooses to sign in as an existing member or a new user to sign up. 

Routes Folders
The API route folders directs all of the traffic. Based on what the user is wants to do will determine the route. If the user is new and wants to register there's is a "create function" that executed to prompts the user to the registration path where they create use an email and create a password. There's a "login function" for existing users where their user name an password are verified before being navigate to the members page.

User.js / passport.js 
The User.js folder handles the existing user / new user registration process making sure that the user doesn't leave the email and password input blank (null). Then the passport.js file is responsible for the verification of existing members. 

Finally the html-routes.js execute all of the front-end html and css accordingly. 










## Credits :star:

S/O - Slack: Study Group 3!!

Lofi Music: https://www.youtube.com/watch?v=tutZKLeGrCs

## Author :pen:

Ernest Wesson :lighting:

LinkedIN: https://www.linkedin.com/in/ernest-wesson-b4183b5a/




## License :clipboard:


MIT License

Copyright (c) [2020] [Ernest]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
