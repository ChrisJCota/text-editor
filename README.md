# text-editor with PWA

## Description
This project is a text editor which allows the user to create code or notes and retrieve them later on. This text-editor uses an integrated service
worker along with a cache API so the project can also function offline.

## Installation
This project requires node and the following packages
* `npm install express (express.js)`
* `npm install idb (IndexedDB)`
* `npm install concurrently --save (run multiple commands concurrently.) (Concurrently)`
* `npm install --save-dev css-loader (CSS-loader)`
* `npm install babel (Babel)`
* `npm install --save-dev webpack-pwa-manifest (WebpackPwaManifest)`
* `npm install webpack-dev-server --save-dev (webpack-dev-server)`
* `npm install --save-dev webpack (Webpack)`

All required modules are in the package.json. To download the bundle run `npm i`

## Usage

``````
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
``````
<img width="1440" alt="Screenshot 2023-05-24 at 9 54 38 PM" src="https://github.com/ChrisJCota/text-editor/assets/118009584/7e34ce95-44a2-4045-a20d-df5100d4ba39">

## References

Module 19 Mini-Project: Deploy Contact Directory App on Heroku with Script

## Links 

Deployed - https://git.heroku.com/my-text-editor-with-pwa.git
Repository - https://github.com/ChrisJCota/text-editor
