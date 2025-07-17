# Dockerized Node.js Sample App

A simple Node.js app to test Docker builds and Jenkins pipelines.

## Run Locally

```bash
docker build -t nodejs-app .
docker run -p 3000:3000 nodejs-app
