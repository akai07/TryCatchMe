# TryCatchMe
Button Game - Click, React, Conquer! Experience the adrenaline rush of clicking the elusive moving button. With adjustable difficulty levels, addictive gameplay, and sleek design, this web-based game will keep you entertained for hours. Challenge yourself now and become the ultimate button master!


Try Here - https://akai07.github.io/TryCatchMe


The given code is an HTML document that implements a simple button game. Here's a breakdown of the different components and functionalities provided by the code:

HTML Structure:

The game is contained within a <div> element with the id "game". It is positioned in the center of the screen using CSS.
The game area includes a button with the id "button" that the player needs to click.
There is a settings button with the id "settings-button" positioned at the top right corner of the screen.
The settings popup is a <div> element with the id "settings-popup" that appears when the settings button is clicked. It contains a difficulty level slider and a "Save" button.
The current difficulty level is displayed in a <div> element with the id "current-level".
CSS Styling:

The background color of the page is set to black (#000000).
The game area is positioned fixed and occupies the entire screen.
The button is styled with a red (#ff0000) background color and white (#ffffff) text color.
The settings button has a white background color and black (#000000) text color.
The settings popup is positioned fixed and appears in the center of the screen. It has a white background color, padding, and rounded corners.
The current difficulty level text is positioned fixed and displayed at the top center of the screen. It has a white text color, large font size, and bold weight.
JavaScript Functionality:

The getRandomPosition() function generates a random position within a specified range.
The moveButton() function moves the button to a random position within the game area by updating its CSS properties.
The handleClick() function is triggered when the button is clicked. It disables further clicks, displays a congratulatory message, and reloads the page to restart the game.
The showSettingsPopup() function displays the settings popup by updating its display style property.
The hideSettingsPopup() function hides the settings popup by updating its display style property.
The startGame() function is called when the "Save" button in the settings popup is clicked. It hides the popup, updates the difficulty level, adjusts the animation speed of the button, and updates the displayed difficulty level.
The updateCurrentLevel() function updates the displayed difficulty level based on the current value of the difficulty level slider.
Event Handlers:

The window.onload event handler sets up the initial state of the game when the page finishes loading. It attaches event handlers to the button click, moves the button at regular intervals, and handles the settings button click. It also initializes the difficulty level and displays it.
Overall, the code implements a simple button game with a movable button and adjustable difficulty level. The player's objective is to click the button as many times as possible within a limited time frame. The code provides a basic user interface and interaction through HTML, CSS, and JavaScript.
