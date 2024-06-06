# Node.js Express Application with Firebase and API Integration

## Overview

This is a Node.js and Express application that allows users to sign up and sign in using Firebase Firestore for user authentication. Additionally, the application integrates with an external thesaurus API to fetch synonyms and antonyms of words entered by the user.

## Features

- User Sign-Up: Users can register with their email and password.
- User Sign-In: Registered users can log in with their credentials.
- Word Data Retrieval: Fetch synonyms and antonyms for a given word using the API Ninjas Thesaurus API.
- Rendering Views: Uses EJS as the templating engine to render views.

## Prerequisites

- Node.js (v12.x or higher)
- npm (v6.x or higher)
- Firebase account with Firestore database
- API Ninjas account for Thesaurus API key

## File Structure

├── views
│   ├── signin.ejs
│   ├── signup.ejs
│   ├── home.ejs
│   └── word.ejs
├── key.json
├── app.js
├── package.json
├── package-lock.json
