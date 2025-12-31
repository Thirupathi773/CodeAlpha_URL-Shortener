# URL Shortener – Task 1

This project is a backend URL Shortener application developed as part of Task 1.
It converts long URLs into short URLs and redirects users to the original website.

## Technologies Used
- Node.js
- Express.js
- MongoDB
- Mongoose
- Postman
- MongoDB Compass

## Features
- Generate short URL for a long URL
- Store URL data in MongoDB
- Redirect short URL to original URL
- REST API based backend

## API Endpoints
### POST /shorten
**Request Body**
json
{
  "originalUrl": "https://google.com"
}
## Respose
json
{
  "shortUrl": "http://localhost:5000/Nh_zX269G"
}

