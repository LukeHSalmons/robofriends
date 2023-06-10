# RoboFriends

RoboFriends is a simple React app that displays a list of robot friends. Users can search for specific robots by name and view their details.

## Features

- Fetches robot data from an external API (https://jsonplaceholder.typicode.com/users) using the `fetch` function.
- Implements a search functionality that filters the robot list based on the entered search term.
- Utilizes the `useState` and `useEffect` hooks to manage state and perform side effects.
- Includes error handling with the `ErrorBoundary` component to catch and display any errors that occur within the `CardList` component.
- Implements a scrollable container using the `Scroll` component.

## Installation

1. Clone the repository: `git clone https://github.com/LukeHSalmons/robofriends.git`
2. Navigate to the project directory: `cd robofriends`
3. Install the dependencies: `npm install`

## Usage

1. Start the development server: `npm start`
2. Open your web browser and visit `http://localhost:3000` to view the app.
