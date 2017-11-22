# React-Contact-List-App

![Contacts List App](https://github.com/nidhigaday/React-Contact-List-App/blob/master/public/Contacts-app.gif)

# Introduction

This is a in-class project in Udacity React Nanodegree. It is intended to learn react functional and class components, state management, and rendering JSX code to the UI based on the state of the component.

## Highlights:

* Used [Create React App](https://github.com/facebookincubator/create-react-app) to bootstrap the project.
* Created a new JS file for each component; following DOT.
* Component state is passed down from parent to child component. SetState() is used to modify the state of the component.

## Folder Structure
```bash
├── README.md
├── package.json # npm package manager file. 
├── npm-debug.log # log file for errors.
├── server.js # server file to run back-end server with the list of contacts. 
├── public # Contains all the image files.
└── src
    ├── icons # Images for the app.
    ├── utils # Contacts backend API file.
    ├── App.js # Root of the app.
    ├── App.test.js # Used for testing.
    ├── CreateContact.js # JS file for the component to create a new contact.
    ├── ImageInput.js # JS file provided by Udacity to add an image to the contact.
    ├── ListContacts.js # JS file for the component to list all the contacts - by default or by filter.
    ├── index.css # Global styles.
    └── index.js # Used for DOM rendering.
```

## Getting Started

* Download this repo
* Open the folder in command line and install all dependecies with `npm install`. If already installed, skip to next step
* Open 'reactnd-contacts-server' folder in command line. Start the backend server by `node server.js`
* Open 'React-Contact-List-App' folder in command line. Run `npm start` to open application



