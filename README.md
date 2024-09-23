# My React Fitness App

A fitness tracking application built with React. This app allows users to log their steps and activities, view their progress, and track calories burned.

## Features

- Log daily steps
- Log various activities with duration
- View progress in a circular progress bar
- Track calories burned
- Responsive design



## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/<your-github-username>/<your-repo-name>.git
   cd <your-repo-name>
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Start the development server:
   ```sh
   npm start
   ```

## Deployment

To deploy the app to GitHub Pages, follow these steps:

1. Install the `gh-pages` package:
   ```sh
   npm install gh-pages --save-dev
   ```

2. Add the following properties to your `package.json` file:
   ```json
   {
     "homepage": "https://<your-github-username>.github.io/<your-repo-name>",
     "scripts": {
       "predeploy": "npm run build",
       "deploy": "gh-pages -d build"
     }
   }
   ```

3. Deploy the app:
   ```sh
   npm run deploy
   ```

## Technologies Used

- React
- CSS
- gh-pages


