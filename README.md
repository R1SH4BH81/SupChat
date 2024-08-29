# Superchat App

A simple Superchat application built using React and Firebase. This app allows users to send and receive messages in real-time during a live stream, similar to YouTube's Superchat feature.

## Features

- **Real-time Messaging:** Messages appear instantly without the need for page refreshes.
- **Firebase Authentication:** Secure user authentication using Firebase.
- **Firebase Firestore:** Real-time database for storing and retrieving messages.
- **Responsive Design:** Fully responsive UI, optimized for both desktop and mobile devices.

## Screenshots
![Live chat](https://firebasestorage.googleapis.com/v0/b/myblog-8800d.appspot.com/o/manifest%2FgithubPinned%2Fsupchat.png?alt=media&token=d40bdd0c-e2fb-4d9b-9d77-699408f31dae)


## Installation

1. **Clone the repository:**
   ```bash
   https://github.com/R1SH4BH81/SupChat.git
   cd SupChat
   ```
2. Install dependencies:

```bash
npm install
```
3 .Set up Firebase:

Create a Firebase project in the Firebase Console.
Add your Firebase config to a .env file in the root directory:

```bash

REACT_APP_FIREBASE_API_KEY=your-api-key
REACT_APP_FIREBASE_AUTH_DOMAIN=your-auth-domain
REACT_APP_FIREBASE_PROJECT_ID=your-project-id
REACT_APP_FIREBASE_STORAGE_BUCKET=your-storage-bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id
REACT_APP_FIREBASE_APP_ID=your-app-id
```
 ### Run the app:

```bash

npm start
```
The app will run on http://localhost:3000/.

## Usage
Sign in using your Google account.
Start chatting in real-time with other users.

## Technologies Used
React: Frontend library for building the user interface.
Firebase: Backend services for authentication and real-time database.
Tailwind CSS: For styling the application.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss any changes.

