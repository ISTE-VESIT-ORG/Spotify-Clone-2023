# Day 1

## Installation and React Setup
- Installation of VSCode and Node.js was left to the attendees as a pre-requisite for the workshop
- After the installation of VSCode and Node.js, React was setup using [`create-react-app`](https://create-react-app.dev/)
- The following commands were run in a convenient directory:
    * `npm i -g create-react-app`
    * `npx create-react-app frontend`
    * `cd frontend`
    * `code .`
- After setting up React the project was setup in VSCode by installing relevant extensions making editing easier
- The following extensions were installed:
    * [ES7+ React/Redux/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)
    * [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
    * [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)

## Tailwind CSS
- Tailwind was setup with React by following the following docs: https://tailwindcss.com/docs/guides/create-react-app

## Sidebar
 - The Sidebar component was developed in the first day after successful setup of React and Tailwind CSS
 - Two more components made up the Sidebar component being [`Sidebar/Menu.js`](/src/components/Sidebar/Menu.js) & [`Sidebar/Playlist.js`](/src/components/Sidebar/Playlist.js)
 - [`Sidebar.js`](/src/components/Sidebar.js) holds the logo and acts as a container for Menu and Playlists components
 - The Menu component has three items Home, Search & Library
 - The Playlists component contains a scrollable list of components iterated over using the [map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map) method
 - This marked the end of Day 1 of the workshop

## Progress after Day 1
![The Sidebar Component](/screenshots/Day1-Sidebar.png)

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.