# RoboFriends

A React app that loads a list of users from an API and shows each one as a robot card. Type in the search box to filter the robots by name as you type.

**Live demo:** https://the-codingphoenix.github.io/RobotFriends/

<!-- Add a screenshot: save one as public/screenshot.png and uncomment the next line -->
<!-- ![RoboFriends screenshot](public/screenshot.png) -->

## Features

- Fetches user data from the JSONPlaceholder API
- Live search that filters cards as you type
- Robot avatars for each user from RoboHash
- Scrollable card list and a loading message while data loads

## Built with

- React 18 (function components, `useState`, `useEffect`)
- Create React App
- Deployed with GitHub Pages (`gh-pages`)

## What I learned

- Splitting a UI into reusable components (`Card`, `CardList`, `SearchBox`, `Scroll`, `ErrorBoundary`)
- Passing data and functions down with props
- Fetching data in `useEffect` and storing it in state
- Rewriting a class component as a function component with hooks

## Run it locally

```bash
git clone https://github.com/the-codingphoenix/RobotFriends.git
cd RobotFriends
npm install
npm start
```

Then open http://localhost:3000.
