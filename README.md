# hangwoman

Link to <a href="https://chotimmysf.github.io/hangwoman/" target="_blank">Live Demo App</a>

<strong>BACKSTORY</strong>

This project was inspired by the "Hangman" project in this <a href="https://www.udemy.com/course/web-projects-with-vanilla-javascript/learn/lecture/17842006#overview" target="_blank">Vanilla JavaScript Course.</a> I was introduced to SVG (Scalable Vector Graphics), as well as more complex uses of JavaScript through more exposure to event listeners and now loops.

<strong>PROJECT JOURNEY INSIGHTS</strong>

In past projects, I had hover effects and click events on their CSS files and event listeners on the JavaScript files to imitate a dynamic app. While doing this project, however, I learned how to change CSS elements dynamically using if/else statements in JavaScript.

<strong>APP OVERVIEW</strong>

1. SVG Graphic

   Lines, polygons, and circle SVG elements are implemented in the HTML via SVG tags.

2. Letters Input

   The user can enter a letter, and if the word contains the letter, it will fill the blanks. (correct letters splice function). Otherwise, the letter will appear under the hangwoman figure as a wrong letter (wrong letters splice function) and part of the hangwoman will display (figure parts loop).

3. End-of-Game Popup

   When the entire hangwoman figure is shown or when the player gets all letters of the word, a loss or win popup appears, prompting the user to play again.

4. New Word Button

   When the game ends, the player will be shown a button that will start the game again, giving the player a new word to guess.

<strong>TECHNOLOGIES USED</strong>

JavaScript

SVG

HTML

CSS

<strong>CHALLENGES</strong>

Time Management: Keeping app development within 1 week scope - I spent 3 weeks building this app.

Lack of Experience: For the "Play Again" button, I tried adding an event listener for the enter key, but this resulted in the word blanks disappearing. Not knowing what to do, I chose to implement this later.

<strong>FUTURE IMPROVEMENTS</strong>

Add code that will prevent any new letters entered to be counted against the figure after the loss/win popup, forcing the player to start again.

Add an ability to restart the game using the enter button on a keyboard.

Add a button on the web app that allows users to switch between word sets.

<strong>MENTOR:</strong>

<a href="https://www.linkedin.com/in/alexsjcho/" target="_blank">Alex Cho - Technical Product Manager</a>
