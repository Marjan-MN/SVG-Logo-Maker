# SVG-Logo-Maker

## Table of Contents

 * [Description](#description)

 * [Live-Screen-Recording-of-Application-Functionality](#live-screen-recording-of-application-functionality)

 * [Screenshots](#screenshots)

 * [Technologies-Used](#technologies-used)

 * [Installation](#installation)

 * [Features](#features)

 * [Test-Instructions](#test-instructions)



 ## Description
This application enables freelance web developers to create simple logos for their clients without hiring a graphic designer. It uses inquirer in the command line to prompt users for their logo preferences, such as text, colors, and shape (triangle, square, or circle). The output is an SVG file with their custom logo. The project also includes my first implementation of unit testing, ensuring correct shapes and colors. In the future, I plan to add error handling for SVG colors, expand the unit tests, and offer more polygons and font styles for users to choose from.

## Live Screen Recording of Application Functionality
https://drive.google.com/file/d/1fTWV0uFgrS5nhjpSoTnqlSdm--xrTm0I/view

![Screenshot1](./assets/Untitled_%20Jul%2017,%202023%2010_12%20PM.gif)

## Screenshots
![Screenshot1](./assets/Screenshot%202023-07-17%20225157.jpg)
![Screenshot1](./examples/logo-example-1.svg)
![Screenshot1](./examples/logo-example-2.svg)
![Screenshot1](./examples/logo-example-3.svg)

## Technologies Used
This project is powered by Node.js v16, utilizes inquirer v8.2.4 (node package manager), and file system module (node package manager). It also employs jest v29.6.1 (node package manager) for the unit testing conducted in this application.

## Installation
1. Clone the repo:
   git clone https://github.com/Marjan-MN/SVG-Logo-Maker

2. Open in VS Code. If you do not have VS code you must install it.

3. Using the terminal, install node.js v16. If you have homebrew, the command should look like the following (brew install node@16), however this may vary and the documentation should be consulted.

4. Once node.js v16 is installed, in the terminal, utilize the command npm init -y to initialize and create a package.json where project files will be stored.

5. Next, use the terminal to run the command npm i to install the dependencies associated with this application (developers may need to install inquirer and jest directly from the command line, to do so the command for inquirer will be npm i inquirer@8.2.4 to install v8.2.4 of the inquirer, and npm i jest to install the latest version of jest).

6. To run the application, within the terminal, type the command node index.js.


## Features
Features of this application include the users ability to generate logos quickly and easily through the use of SVG files, entirely from the command line. No UI (user interface) needed, and no front end tools needed.  

## Test Instructions
To run unit testing, open the terminal, and use the command npm run test.
As of now there is one test suite with three tests. The test suite is checking for a render() method to return a string for the corresponding SVG file with the given shape color.

![Screenshot1](./assets/Screenshot%202023-07-17%20225023.jpg)