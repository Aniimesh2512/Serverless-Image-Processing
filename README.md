# Serverless Image Processing App

This is a simple web application that allows users to upload images, which are then automatically resized and optimized using a serverless backend powered by AWS Lambda and S3.

## Features

- Upload images via a React frontend
- Images are resized and compressed using AWS Lambda with Sharp
- Optimized images are stored in an S3 bucket
- Returns a URL for the optimized image

## Tech Stack

- **Frontend:** React, Axios
- **Backend:** AWS Lambda (Node.js), API Gateway, S3, Sharp

## Getting Started

### Frontend

```bash
cd frontend
npm install
npm start
