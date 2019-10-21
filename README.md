# Movies Rental App

**Notes**: This repo put two separate repo together for ease of access and viewing. The backend was originally at https://github.com/vuongdieuban/store_node and frontend was at https://github.com/vuongdieuban/store_react


## Description:
This app is a Single Page Application (SPA) mock up of a video rental service, where employees can rent out movies to customers. Role based authentication and authorization allow employees to create/update/delete movies, rentals and returns.

The live demo is at: http://movies.banvuong.com/movies

## Details:
### Backend
**Technologies Used**:  NodeJs, ExpressJs, MongoDB, JSON Web Token (JWT), Jest.

1) Implemented REST API CRUD endpoints to interface with the database MongoDB
2) Protected route, authentication and authorization with JWT.
3) Server side validation with Joi.
4) Unit test and Integration test with Jest.
5) Followed MVC design patter and clean code practice

### Frontend
**Technologies Used**: Javascript/ReactJs, HTML5, CSSS3, Bootstrap 4

1) Perform CRUD operations with REST API from the backend.
2) Client side form/input validation.
3) Responsive design.
4) Follow ReactJS components based approach for ease of code re-use.

### Deployment
Deploy both frontend and backend on Digital Ocean Droplet (Virtual Private Server - Ubuntu Linux). Use Nginx to serve the frontend, PM2 to serve the backend. 