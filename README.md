# Sportswriter Academy

A responsive sports journalism training app featuring:
- 150 practice prompts across 15 sports and 30 story angles
- Lead Lab and Play-by-Play Trainer
- 16-section Composite Article Studio
- Sports vocabulary practice
- Local browser saving, JSON backup export/import
- Optional Firebase email/password sign-in and Firestore sync

## Run in Visual Studio Code
1. Extract the ZIP.
2. Open the `sportswriter-academy` folder in VS Code.
3. Install the **Live Server** extension.
4. Right-click `index.html` and choose **Open with Live Server**.

The app works without Firebase. Progress is saved in the browser on that device. Export a backup before changing browsers or devices.

## Optional cloud sync
1. Create a Firebase project and add a Web App.
2. Enable Email/Password under Authentication.
3. Create a Cloud Firestore database.
4. Paste your Firebase web app config into `firebase-config.js`.
5. Apply the included `firestore.rules` in Firestore Rules.
6. Host the app on HTTPS (for example GitHub Pages).
7. Create an account in the app, sign in, then choose **Sync now**.

The Firebase config is not a password, but Firestore security rules are essential. Ask a parent or guardian to help with account setup. Avoid putting personal information in public drafts.

## Accuracy reminder
The writing reviewer checks basic writing patterns; it does not verify facts. Prompts are fictional practice scenarios. For real articles, verify every score, player action, and quote against reliable match coverage or footage.
