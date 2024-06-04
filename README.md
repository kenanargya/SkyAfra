## Prerequisites

- [Node.js](https://nodejs.org/) (v12 or later)
- [npm](https://www.npmjs.com/get-npm) (v6 or later)
- [Firebase CLI](https://firebase.google.com/docs/cli) (optional, for advanced Firebase setup)

## Firebase Setup

1. **Create a Firebase Project**
   - Go to the [Firebase Console](https://console.firebase.google.com/).
   - Click on "Add project" and follow the steps to create a new Firebase project.

2. **Add a Service Account**
   - Navigate to `Project Settings` > `Service accounts`.
   - Click on `Generate new private key` and download the JSON file. Save this file as `key.json` in the root directory of your project.

3. **Enable Firestore**
   - In the Firebase Console, go to `Firestore Database` and click on `Create database`.
   - Follow the steps to set up Firestore in production or test mode.
