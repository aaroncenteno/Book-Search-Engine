![License](https://img.shields.io/static/v1?label=License&message=MIT&color=BLUE)

# Book Search Engine

## Description

This weeks challenge was to take a application that used express API routes and refactor it to use an Apollo Server and GraphQL queries and mutations. This application allows a user to search google books via google's API and then view that books information. If the user decides to sign-up then they can save their searched books to their account and view their saved books as well. On the '/saved' page users can see their saved books and choose to remove them if they would like. 

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contributing](#contributing)
* [Technologies Used](#technologies-used)
* [Bugs & Enhancements](#bugs-&-enhancements)
* [Links](#links)
* [Questions](#questions)

## Installation 

Run 'npm install' in the command line to install all the necessary dependencies if trying to run the app locally.

## Usage

To access this application simply navigate to https://desolate-plains-77425.herokuapp.com/ and begin browsing my projects. 

## Licenses

* MIT

## Contributing

* Aaron Centeno

## Technologies Used
* Node Modules
* GitHub
* JavaScript
* React.js
* Terminal
* CSS
* GraphQL
* Apollo Server

## Bugs & Enhancements 

One of the bugs or rather functionalities of the code that I tried to enhance was the remove book. When the button to remove a book is clicked the page remains the same and must be reloaded to actually see the result. I wanted to have the cache update when the button is clicked, but I could not seem to figure out how to do that. When I used the update cache with $pull it would pull everything in the savedBooks object and leave the first book. Then on reloading the remaining books would populate, with the removed book being gone. This was close to what I wanted to happen but not completely. Please see the commented out code on lines 16-35 in "client/src/pages/SavedBook.js". If there is any reccommendations, please contact me. 

## Screenshots

<img src="./public/assets/imgs/book-search-engine.png">

## Links

Live App: https://desolate-plains-77425.herokuapp.com/

GitHub Repo: https://github.com/aaroncenteno/book-search-engine

## Questions

Contact Information for questions: 


GitHub: [aaroncenteno](https://www.github.com/aaroncenteno) 

E-mail: asamcent@gmail.com