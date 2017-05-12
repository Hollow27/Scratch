# Scratch
A Simple Note Taking App: It is a single page application powered by a serverless API written completely in JavaScript. 

# Why Serverless Apps?
It is important to address why it is worth learning how to create serverless apps. There are a couple of reasons why serverless apps are favored over traditional server hosted apps.

- Low maintenance
- Low cost
- Easy to scale

The biggest benefit by far is that you only need to worry about your code and nothing else. And the low maintenance is a result of not having any servers to manage. You don’t need to actively ensure that your server is running properly or that you have the right security updates on it. You deal with your own application code and nothing else.


The following is a complete source for the backend and the frontend. It is a relatively simple application but I'm going need to address the following requirements.

- Should allow users to signup and login to their accounts
- Users should be able to create notes with some content
- Each note can also have an uploaded file as an attachment
- Allow users to modify their note and the attachment
- Users can also delete their notes
- App should be served over HTTPS on a custom domain
- The backend APIs need to be secure
- The app needs to be responsive
- We’ll be using the AWS Platform to build it. We might expand further and cover a few other platforms but we figured the AWS Platform would be a good place to start. 

I’ll be using the following set of technologies to build our serverless application.

- Lambda & API Gateway for our serverless API
- DynamoDB for our database
- Cognito for user authentication and securing our APIs
- S3 for hosting our app and file uploads
- CloudFront for serving out our app
- Route 53 for our domain
- Certificate Manager for SSL
- React.js for our single page app
- React Router for routing
- Bootstrap for the UI Kit

This may seems a little overwhelming; however, the end product will be a real-world, secure, and fully-functional web app. 

The project will cover the following concepts:

For the backend:

- Configure your AWS account
- Create your database using DynamoDB
- Set up S3 for file uploads
- Set up Cognito User Pools to manage user accounts
- Set up Cognito Identity Pool to secure our file uploads
- Set up the Serverless Framework to work with Lambda & API Gateway
- Write the various backend APIs

For the frontend:

- Set up our project with Create React App
- Add favicons, fonts, and a UI Kit using Bootstrap
- Set up routes using React-Router
- Use AWS Cognito SDK to login and signup users
- Plugin to the backend APIs to manage our notes
- Use the AWS JS SDK to upload files
- Create an S3 bucket to upload our app
- Configure CloudFront to serve out our app
- Point our domain with Route 53 to CloudFront
- Set up SSL to serve our app over HTTPS

All credits go to Jay and Frank at www.serverless-stack.com

Appreciate what you two are doing!
