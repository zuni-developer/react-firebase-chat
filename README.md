# React Firebase Chat

A real-time chat application built with React and Firebase. Users can sign in with Google, send messages instantly, and communicate in a modern chat interface powered by Firebase services.

## Features

* Real-time messaging with Cloud Firestore
* Google Authentication with Firebase Auth
* Responsive chat interface
* Automatic message synchronization
* Serverless backend using Firebase
* Secure user authentication

## Tech Stack

* React
* Firebase Authentication
* Cloud Firestore
* Firebase Hosting
* JavaScript
* CSS

## Getting Started

### Prerequisites

* Node.js (v16 or later recommended)
* npm
* Firebase account

### Installation

1. Clone the repository:

```bash
git clone https://github.com/zuni-developer/react-firebase-chat.git
cd react-firebase-chat
```

2. Install dependencies:

```bash
npm install
```

3. Create a Firebase project and enable:

* Authentication (Google Sign-In)
* Cloud Firestore

4. Add your Firebase configuration in the project:

```javascript
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID",
};
```

5. Start the development server:

```bash
npm start
```

## Available Scripts

```bash
npm start      # Run development server
npm run build  # Create production build
```

## Deployment

Build the application:

```bash
npm run build
```

Deploy to Firebase Hosting:

```bash
firebase deploy
```

## Learning Resource

This project is based on the React Firebase Chat tutorial by Fireship and serves as a practical example of building real-time applications with Firebase.

Watch the full [React Firebase Chat Tutorial](https://youtu.be/zQyrwxMPm88) on YouTube. 
