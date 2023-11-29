# Day 2

## Context API

- Context API was used to pass information of songs to the [`Bottombar/Player.js`](/src/components/Bottombar/Player.js) and proceed accordingly
- The state is managed through [`SongState.js`](/src/context/SongState.js) and the context is created using [SongContext.js](/src/context/SongContext.js)
- The following state variables and functions were created and exported through context:
  - songs, setSongs
  - currentSong, setCurrentSong
  - isplaying, setIsplaying

## Bottombar

- The Bottombar component was developed in the second day
- This involved designing the bottom bar as well as writing the song playing logic
- Bottombar is composed of another component [`Bottombar/Player.js`](/src/components/Bottombar/Player.js)
- The Player component contains the styling of the bottom bar of tha page
- It is also used to fetch and play songs from [`Bottombar/audios.js`](/src/components/Bottombar/audios.js) along with providing additional functionality like skipping to the to next or previous song
- This marked the end of Day 2 of the workshop

## Progress after Day 2

![The Bottombar Component](/screenshots/Day2-Bottombar.png)

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
