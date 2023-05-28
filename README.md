# MERN_Social_Media_Platform

a social media platform built using MERN tech stack

![home](imgs/darkHome.png?raw=true)

![home](imgs/lightHome.png?raw=true)

# Dependencies

Express: Fast, unopinionated, and minimalist web framework for Node.js.
body-parser: Node.js body parsing middleware for handling HTTP requests.
bcrypt: A library to help you hash passwords.
cors: Cross-Origin Resource Sharing (CORS) middleware for Express.js.
dotenv: Loads environment variables from a .env file into process.env.
gridfs: A MongoDB GridFS storage library for Node.js.
multer: Middleware for handling multipart/form-data (e.g., file uploads) in Express.js.
helmet: Helps secure your Express.js apps by setting various HTTP headers.
morgan: HTTP request logger middleware for Node.js.
jsonwebtoken: An implementation of JSON Web Tokens (JWT) for Node.js.
mongoose: A MongoDB object modeling tool designed to work in an asynchronous environment.

# Setting the MongoDB database

go to mongodb website create an account or login get the connection url file and place it in the .env file in the MONGO_URL variable

# populating fake data

if you want to populate fake data to the mongodb uncomment the following code in server/index.js run it then comment it again.

![code](imgs/uncomment.png?raw=true)
