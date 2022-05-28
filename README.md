# Project Auth API
This is a group project by Amanda, Michael and Stephannie. 
For this project we built a backend and a frontend at the same time.
Using an API that was created in the backend we then used it to build a registration flow.
Other learning goals included:

- how to authenticate users using tokens
- How to securely store passwords in your databases
- How to handle authentication, both in the frontend and in the backend

## The problem

Describe how you approached to problem, and what tools and techniques you used to solve it. How did you plan? What technologies did you use? If you had more time, what would be next?
To style this project we installed mui/material and styled components. Another technology was reduxjs/toolkit.
A problem occured from backend side when adding a min- and maxlength to our password property in the model Schema. Since we are using encrypted password the length of this becomes longer than allowed. This was solved by just keeping a validation for password from frontend side.  

## View it live
https://haveyouseenmebro.netlify.app/
