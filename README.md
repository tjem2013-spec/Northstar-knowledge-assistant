# Northstar Knowledge Assistant

AI-assisted customer support knowledge assistant for Northstar Home Services.

## Local run
Install Node.js 20+, then:

    npm install
    npm start

Open http://localhost:3001

## AWS App Runner
This project includes a Dockerfile and is ready for deployment to AWS App Runner. Create a service from the GitHub repository, use the Dockerfile configuration, and set the port to 3001. App Runner will provide a public Default domain after deployment.

## Architecture
React frontend (loaded from React CDN), Node.js/Express backend, grounded Northstar knowledge base, Docker container, AWS App Runner deployment.
