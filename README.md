# jQuery API Manipulation

## Table of Contents
1. [Introduction](#introduction)
2. [Learning Objectives](#learning-objectives)
3. [Resources](#resources)
4. [Requirements](#requirements)
5. [Setup Instructions](#setup-instructions)
6. [Usage](#usage)
7. [GitHub Repository](#github-repository)
8. [Manual QA Review](#manual-qa-review)
9. [Contributors](#contributors)

## Introduction
This project focuses on using jQuery to manipulate the DOM, make GET and POST requests, and handle events. By the end of this project, you will be able to create and modify elements in the DOM, style elements, and interact with APIs using jQuery.

## Learning Objectives
At the end of this project, you should be able to explain the following concepts to anyone:
- How to request your own API
- How to modify an HTML element style
- How to get and update an HTML element's content
- How to manipulate the DOM
- How to make GET requests with jQuery Ajax
- How to make POST requests with jQuery Ajax
- How to listen and bind to DOM events
- How to listen and bind to user events

## Resources
Read or watch:
- [Selector](https://api.jquery.com/category/selectors/)
- [Get and set content](https://api.jquery.com/category/manipulation/)
- [Manipulate CSS classes](https://api.jquery.com/category/css/)
- [Manipulate DOM elements](https://api.jquery.com/category/manipulation/)
- [Document ready](https://learn.jquery.com/using-jquery-core/document-ready/)
- [Introduction](https://jquery.com/)
- [GET & POST request](https://learn.jquery.com/ajax/)
- [HTTP access control (CORS)](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS)

## Requirements
- Allowed editors: `vi`, `vim`, `emacs`
- All your files will be interpreted on Chrome (version 57.0)
- All your files should end with a new line
- A `README.md` file at the root of the folder of the project is mandatory
- Your code should be semistandard compliant: `semistandard *.js --global $`
- All your JavaScript must be in the folder `scripts`
- You must use jQuery version 3.x
- You are not allowed to use `var`
- HTML should not reload for each action: DOM manipulation, update values, fetch data…

## Setup Instructions
### Install Flasgger and Dependencies
Before starting the project, you need to install Flasgger locally:
```bash
$ sudo apt-get install -y python3-lxml
$ sudo pip3 install flask_cors
$ sudo pip3 install flasgger

