# Zing Assessment Centre - Group Work Assessment

For this assessment, you will be placed into groups of two or three. You will be assessed on your communication skills, ability to develop code, collaborate, and problem solve individually and as part of a team.  
Do not worry if you do not finish all of the requirements for the app; do as much as possible within the time limit.  
If you need any information please ask.  

Your assignment is to build an app with the following requirements:

* The app must use React (JavaScript) as the frontend. You will be required to fetch some data from an external API but will not be required to write any backend code.
* The app should have at least two inputs: one for longitude, and one for latitude. These can be simple input boxes for typing numbers in, and both should be labelled.
* The app should have a search button that you can click on.
    * The search button should only be clickable if the longitude and latitude boxes have numbers in them
    * The search button's background colour should be blue
* The app must use the open-meteo API to fetch data, based on the longitude and latitude that are inputted.
    * The open-meteo API can be found at https://open-meteo.com/en
    * HINT: Have a look at the fetch API at https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API for how to fetch data from the open-meteo
    * OR: Have a look at the open-meteo package on NPM
    * After fetching the data, you can then display this in your app
* Extension tasks:
    * Update the display to also include the time that the temperature was recorded
    * If the user puts a string instead of a number in the longitude or latitude box, display a validation warning near to the relevant box
    * Make your input boxes, button and temperature information centred on the page
    * Make your background image an image of a bright blue sky
    * Add anything else that you think makes this app more presentable

## Setup Steps:

1. We'll use Vite as a quick way to get started with React. Follow this link to spin up a temporary environment in StackBlitz to start developing: https://vite.new/react.
2. React apps will start their lifecycle from the src/App.jsx file. Try editing some of the HTML here to see how you can change the app.
3. Once you have the basic editing in hand, start to build following the requirement set above.
4. https://react.dev is a great learning site for React, and they have a quick start guide: Quick Start – React
5. Remember, we're not assessing you on code quality or quantity here. We strongly encourage you to ask questions of us, we'll be around the room to help out!  And make use of Google / StackOverflow / GPT (but don't blindly copy code of course).

