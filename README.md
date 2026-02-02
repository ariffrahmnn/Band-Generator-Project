# Band name generator
- Main focused 🎯: EJS Templating, EJS Layout, Basic Js
- Duration ⏰: 3 Hours

## What i did:
- Set up a basic Express server to handle web requests.
- Used express.static("public") to serve static files like CSS.
- Used body-parser to read form data sent from the browser.
- Created a helper function dynamicYear() to dynamically generate the current year and send it to the view.
- Built a GET route ("/") to render the homepage using EJS and pass the current year.
- Created generateNameBasedOnAdj() to randomly select an Adjective.
- Created generateNameBasedOnNoun() to randomly select an Noun.
- Built a POST route ("/submit") that Generates a random name by combining an adjective and a noun and Sends the generated name and current year back to the EJS template.
- Used EJS templating to display dynamic data (year and generated name) in the HTML page.

## Key Concepts
- Express
- Server-side Rendering
- Dynamic Data
- Separation of Logic

note: This project is not originally from me. this based on tutorial by Dr. Angela Yu ❤
