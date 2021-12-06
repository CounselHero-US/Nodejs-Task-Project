# Nodejs Task Project

In this test,developer need to create all the neccessary helpers, constants, models, actions and routes using Nodejs/Expressjs and MongoDB. It would be really nice if you can use TypeScript for the project but it is optional. The main purpose of the test is to see how much the developer knows JavaScript/TypeScript(Optional), NodeJS, ExpressJS, way of coding and project structuring.

### Requirements
Project have to be done using NodeJS/ExpressJS and Mongoose in Javascript or TypeScript.

### Project's Description

1. There are multiple organizations (oragnization can be high school, middle school or primary school) in database (name, location, address, website, city(US), timestamp, and etc)
2. There are multiple counselors inside a organization (username, email address, first name, last name, password, organization id and etc)
3. There are multiple student under a counselor (username, email address, first name, last name, password, couselor id, organization id, and etc)
4. Counselor and student can login to the system using username (make sure it is username not email address) and password. In login endpoint, if login success it will return JWT token and refresh token. If credential are wrong, it will provide respective error message and status code. 
5. In refresh token endpoint, it will provide new token and new refresh token
6. A counselor can create, update and delete event (event name, event thumbnail, event background image, event description(html content), date and time)
7. Student can see and participate multiple events at once if that events were created inside the same organization.
8. Counselor the one who created that event can see the list of participated student, approve or reject the participation.


> Note: The way coded, project structure, optimization and database designing are main focus point of the project. If you can use TypeScript, it will be add as an extra point.

### Submitting
When you finished you project, please upload the source code to the GitHub/GitLab or BitBucket and share us repository link to us by using [minlwin.kyaw@counselhero.com](mailto:minlwin.kyaw@counselhero.com) or info@counselhero.com

Thank you so much in advanced and good luck.
