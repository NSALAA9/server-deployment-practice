# server-deployment-practice

A simple Express server application with middleware functions for handling routes and error handling.

## Deployment

The application is deployed using [Render](https://render.com/), a cloud service provider. You can access the deployed app using the following URL:

[App URL](https://server-6xrv.onrender.com)

## GitHub Actions

Continuous Integration (CI) is set up using GitHub Actions. The workflows are defined in the [github/workflows](https://github.com/NSALAA9/server-deployment-practice/actions/runs/5243054450), 
[mergedPR](https://github.com/NSALAA9/server-deployment-practice/actions/runs/5243064267) directory. You can view the status and details of the GitHub Actions workflows by visiting the Actions tab of your GitHub repository.

## Pull Requests

To contribute to this project, please create a pull request. You can find the open pull requests and create a new one by visiting the [Pull Requests](https://github.com/NSALAA9/server-deployment-practice/pulls?q=is%3Apr+is%3Aclosed) section of your GitHub repository.


## Features

- Middleware functions for request stamping 

- Route handlers for the home page and a bad request page
- Error handling middleware for handling 404 and 500 errors

## Prerequisites

- Node.js (v18.15.0)
- npm (9.5.0)


