# Result Management System
A full-stack MERN application that manages student results.

M - MongoDB -> Database
E - ExpressJS -> Framework for Handling HTTP requests, Error Handling, Routing, etc.
R - ReactJS -> Frontend Components (UI)
N - NodeJS -> Runtime Environment to run JavaScript on the server side.

# Backend Components
models (dir) -> Contains Schemas and Models. <br />
index.js -> Backend Server code for communication between Frontend and Database. <br />
config.js -> Contains important URLs and Connection strings <br />

# Frontend components (/src/components)
Home.js -> Home Page with Navigation to Other pages. <br />
Login.js -> Login for Admins (For publishing the results to Database) <br />
ViewResults.js -> Displays results using student credentials and lets you download/print the result. <br />
AddResults.js -> Page where Admins post results to the database. <br />
