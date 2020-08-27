# Mini Project: Warning when put the hand on your face

## Date: 21 - Mar - 2020

### Functions

Using camera for AI tracking your face & training
After that Application show warning when you put the hand on your face

### Screenshot
<img src="https://i.imgur.com/DAviqwF.png" />
<img src="https://i.imgur.com/bapf8EI.png" />

### Tech-Stack
- @tensorflow-models/knn-classifier : AI tracking & training
- @tensorflow-models/mobilenet : AI tracking & training
- howler : open audio
- mycv/f8-notification : push notifications
- ReactJS for UI

### Directory Structure
```
.
├── .gitignore
├── package.json
├── README.md
├── public
└── src
    ├── assets
        └── hey_sondn.mp3
    ├── App.js
    ├── App.css
    ├── index.css
    └── index.js
``` 

### Set up

Use the cmd line to clone repo to your computer
```
git clone [github_repo_url]
```
Use the cmd line to install dependencies.
```
npm install
```
Run in cmd for start the dependencies server
```
npm start
```
