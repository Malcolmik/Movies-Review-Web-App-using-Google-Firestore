# Movies Review Web App using Google Firestore

This is a simple HTML and JavaScript web application that allows users to manage a collection of movie reviews using Google Firestore as the backend database. The app provides full CRUD functionality (Create, Read, Update, Delete) and sorting features for all fields.

## Features

- Add a movie review with:
  - Movie Name
  - Rating (integer between 0 and 5)
  - Director's Name
  - Release Date
- View all reviews in a clean, tabular format
- Sort reviews by any field (movie name, rating, director, or release date)
- Edit and update individual reviews
- Delete individual reviews
- Real-time data syncing with Firestore
- No authentication required

## Technologies Used

- HTML5
- JavaScript
- Google Firestore (Firebase)
- Firebase SDK

## Setup Instructions

1. Create a Firebase project at [https://console.firebase.google.com](https://console.firebase.google.com)
2. Enable Firestore Database in the Firebase console
3. Copy your Firebase configuration snippet and add it to the HTML file
4. Open `index.html` in your browser to run the app
5. Start managing your movie reviews directly from the browser
