# Text-Editor
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

A simple text editor application that can run both online and offline. This application can be downloaded to your desktop as an application as well.

## Table of Contents

- [Built With](#built-with)
- [Installation](#installation)
- [Usage](#usage)
- [Preview](#preview)
- [License](#license)

## Built With



## Installation

To run this application:
- Install the required packages via `npm install` in the console of the root folder
- Input `npm run start` to start the application

## Usage

- AS A developer
- I WANT to create notes or code snippets with or without an internet connection
- SO THAT I can reliably retrieve them for later use

- GIVEN a text editor web application
- WHEN I open my application in my editor
- THEN I should see a client server folder structure
- WHEN I run `npm run start` from the root directory
- THEN I find that my application should start up the backend and serve the client
- WHEN I run the text editor application from my terminal
- THEN I find that my JavaScript files have been bundled using webpack
- WHEN I run my webpack plugins
- THEN I find that I have a generated HTML file, service worker, and a manifest file
- WHEN I use next-gen JavaScript in my application
- THEN I find that the text editor still functions in the browser without errors
- WHEN I open the text editor
- THEN I find that IndexedDB has immediately created a database storage
- WHEN I enter content and subsequently click off of the DOM window
- THEN I find that the content in the text editor has been saved with IndexedDB
- WHEN I reopen the text editor after closing it
- THEN I find that the content in the text editor has been retrieved from our IndexedDB
- WHEN I click on the Install button
- THEN I download my web application as an icon on my desktop
- WHEN I load my web application
- THEN I should have a registered service worker using workbox
- WHEN I register a service worker
- THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
- WHEN I deploy to Heroku
- THEN I should have proper build scripts for a webpack application

## Preview

- Deployed Application
![image](https://user-images.githubusercontent.com/114375310/224184541-f8fd7a32-e2be-46dd-b307-009acb68cde9.png)

- Service Worker
![image](https://user-images.githubusercontent.com/114375310/224184667-be355c9c-e768-4ac0-9d6a-23742e9aa9f1.png)

- Loaded Manifest 
![image](https://user-images.githubusercontent.com/114375310/224184760-b3c7d890-6b21-4278-8a41-758d8d1c39e5.png)

- Saves locally in indexedDB
![image](https://user-images.githubusercontent.com/114375310/224184872-e7056896-435c-4e52-9120-019300183389.png)

- Offline Capabilities
![image](https://user-images.githubusercontent.com/114375310/224184985-d06bf9a3-2813-4ffb-8e3a-f525bd0b4e6f.png)

- Installed application via PWA
![image](https://user-images.githubusercontent.com/114375310/224185055-d37a4144-538d-491d-9ee0-90ff590c939e.png)

https://stark-wave-50545.herokuapp.com/

## License

See LICENSE in repo