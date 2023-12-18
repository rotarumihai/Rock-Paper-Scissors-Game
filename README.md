# Rock-Paper-Scissors-Game

This Rock Paper Scissors game is a simple web application built using JavaScript, HTML5, and CSS. The server functionality is implemented with the HTTP and FS modules in Node.js. You can run the game by typing the following command in the terminal:

**node app.js**

## Instructions

    Open your terminal and navigate to the project directory.
    Run the game by typing node app.js and press Enter.
    Open your web browser and go to http://localhost:4001.
    Play the Rock Paper Scissors game against the computer.

## How to Play

    Choose your move by clicking on the corresponding button (Rock, Paper, or Scissors).
    The computer will randomly select its move.
    The winner of the round will be displayed on the screen.
    Play as many rounds as you like and enjoy the game!

## Project Structure

    app.js: The main entry point of the Node.js application, handling server setup and routing.
    index.html: The main HTML file for the game.
    404.html: Custom error page for handling 404 requests.

## Server Implementation

The server is created using the HTTP module in Node.js, and it handles both GET and POST requests. The routing is based on the URL pathname, with a switch statement directing requests to the appropriate handlers.

    GET requests to the root path ("/") serve the main game page (index.html).
    POST requests to the root path ("/") are processed by the handlePostResponse function.
    Requests to any other path result in a 404 error, with the user directed to a custom 404 page (404.html).

## Dependencies

    Node.js: Ensure that Node.js is installed on your machine. You can download it from https://nodejs.org/.

Feel free to fork, modify, and have fun playing the game! If you have any suggestions or issues, please open an issue.

**Happy gaming!**
