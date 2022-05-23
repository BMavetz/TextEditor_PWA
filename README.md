# Text Editor PWA
  
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/Apache-2.0)
  
## Description

The text editor implements a PWA, progressive web application, fro use with or without internet connection.  Starter code was provided for the application, and the remainder of the code had to be completed to create a functional note taker app that can be installed on the local system as an application to be used with or without internet. This allowed the application to be turned into a PWA.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [Features](#features)
- [License](#license)

## Installation

Visit [https://whispering-castle-75846.herokuapp.com/](https://whispering-castle-75846.herokuapp.com/) for the application. No further steps are needed to use it in the browser. To use the application outside of the browser, click the install button found on the webpage when accessing the previously mentioned link.  This should add an icon to your desktop that will open the app.

## Usage

The text editor can be used for writing, editing, and saving code.

![screenshot](./assets/textEditor_img.JPG)

## Credits

Collaborators
- N/A

Third Party Assets
- N/A

Tutorials
- N/A

## Features

- Edit text. Save in browser storage. Download to use offline.

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```


## License

This app is covered by the MIT license. For more information, visit https://opensource.org/licenses/Apache-2.0.

## Live Link

[Application](https://whispering-castle-75846.herokuapp.com/)