# react-redux-firebase-auth
Ready to go authentication with Firebase (Email, Google)

![Screenshot](https://github.com/andreysaf/react-redux-firebase-auth/blob/master/screen.png?raw=true "Screenshot")

## Install

```
npm install
```

This application uses Firebase to store PDFs and data for signatures. You can use any other backend of your choice. 
However, to get started with this sample, please register a new app with [Firebase](https://firebase.google.com/).

After you have registered an app, create `.env` file in the root of the directory and place the following:

```
REACT_APP_API_KEY=your_key_goes_here
REACT_APP_MESSAGING_SENDER_ID=your_key_goes_here
REACT_APP_APP_ID=your_key_goes_here
REACT_APP_AUTH_DOMAIN=your_domain_goes_here
REACT_APP_DATABASE_URL=your_database_go_here
REACT_APP_PROJECT_ID=your_project_id
REACT_APP_STORAGE_BUCKET=your_storage_bucket
```
The above information can be found under settings of your Firebase app.
![Screenshot](https://github.com/PDFTron/pdftron-sign-app/blob/master/firebase.png)

Make sure you create a storage bucket, and enable authentication for email and Google.
![Screenshot](https://github.com/PDFTron/pdftron-sign-app/blob/master/firebase_authentication.png)

## Run the app

You can run the app by typing in the terminal

```
npm start
```

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.
