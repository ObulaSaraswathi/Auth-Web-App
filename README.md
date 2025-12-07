React Firebase Authentication Web App


A simple and clean authentication web app built with React and Firebase. It allows users to Sign Up, Login, and access a Dashboard. User credentials are securely stored using Firebase Authentication.

This project is fully functional and ready to deploy on Vercel, Netlify, or Render.

Features

Clean and simple UI for Sign Up and Login pages

Email/password authentication using Firebase

Form validation and proper error messages

Dashboard with welcome message after login

Logout functionality

Navigation between Login and Signup pages

Tech Stack

Frontend: React (Create React App)

Authentication / Backend: Firebase Authentication

Routing: React Router DOM

Hosting: Vercel / Netlify / Render

Setup & Installation

Clone the repository

git clone https://github.com/your-username/auth-webapp.git
cd auth-webapp


Install dependencies

npm install


Firebase setup

Go to Firebase Console
 and create a new project.

Enable Email/Password Authentication in Firebase Authentication.

Copy your Firebase config and replace the values in src/firebase.js:

const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID"
};


Run the app locally

npm start


Open http://localhost:3000
 to view the app.

/login → Login page

/signup → Signup page

/dashboard → Dashboard page after login

Deployment

This app can be deployed easily using Vercel, Netlify, or Render:

Push the repository to GitHub.

Go to Vercel
, click New Project, and import the GitHub repo.

Vercel automatically detects React and deploys your app.

Share the live link after deployment.

Usage

Sign Up: Create a new account using email and password.

Login: Use registered email/password to login.

Dashboard: After login, you are redirected to a dashboard page with a welcome message.

Logout: Click the logout button to return to the login page.

