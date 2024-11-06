# React-Dev-Tools

# Conditional Form Rendering App

A React application that dynamically renders a login or registration form based on the user’s registration status. This project demonstrates how to conditionally render form elements and button text using props in React.

## Table of Contents

1. [Overview](#overview)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Features](#features)
5. [Technologies](#technologies)
6. [Folder Structure](#folder-structure)
7. [Scripts](#scripts)
8. [License](#license)

## Overview

The Conditional Form Rendering App uses a `userIsRegistered` boolean variable in the `App` component to determine if the user is registered. This variable is passed as a prop to the `Form` component, where it controls the rendering of a "Confirm Password" field and adjusts the button text between "Login" and "Register." 

## Installation

### Prerequisites

- Node.js (version 14 or above)
- npm (version 6 or above)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/jbolan12/React-Dev-Tools.git


   Navigate to the project directory:

bash
cd your-repo

## Install the dependencies:

bash
npm install

**Start the development server:**

bash
npm start
Open your browser and go to http://localhost:3000 to view the app.

## Usage
The userIsRegistered variable, located in App.js, controls whether the form is rendered for a registered user (login form) or an unregistered user (registration form). You can toggle userIsRegistered to true or false to test both form states.

**Example**
In App.js:
javascript

var userIsRegistered = false; // Set to true for login, false for registration


## Features
Conditional Rendering: The Form component displays different form fields based on the isRegistered prop:

- If isRegistered is true, only "Username" and "Password" fields are shown, with a "Login" button.
- If isRegistered is false, a "Confirm Password" field is added, and the button text changes to "Register."
- Reusable Form Component: The Form component adapts its layout based on props, making it versatile for login and registration.

## Technologies
- React
- JavaScript (ES6+)
- CSS (custom styling in styles.css)


## Scripts
The following scripts are available in the project:

- start: Runs the app in development mode with react-scripts start.
- build: Builds the app for production using react-scripts build.
- test: Runs the test suite with react-scripts test --env=jsdom.
- eject: Ejects the app from Create React App configuration.


## License
This project is licensed under the MIT License.
