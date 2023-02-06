# Hack-or-Snooze
AJAX with jQuery Exercise
A news-aggregator site inspired by Hacker News that allows users to create accounts, log in, create articles, mark articles as favorites, and more.
### Live website 👉 https://cng008.github.io/16_Hack-or-Snooze/

## Part 0: Explore Working Version and API

1. Visit the working copy of the solution to understand the app and its features.
2. Turn on the browser console to view debugging messages that will help you understand the app.
3. Learn about the API by reading the quickstart section and trying out API calls in Insomnia or curl.

## Features

- The front-end app consists of two parts:
  1. Classes and methods for data management, handling interactions with the API.
  2. Functions for the UI, handling form values and manipulating the DOM.
`js/models.js` contains the data layer of the app, classes that manage data and connection to the API.
The UI layer is divided into several files:
- `js/main.js` contains code for starting the UI.
- `js/user.js` contains code for UI related to logging in/signing up/logging out.
- `js/stories.js` contains code for UI related to listing stories.
- `js/nav.js` contains code for show/hide operations in the navigation bar.
Read the codebase thoughtfully, by skimming it first to understand the classes and functions.
Consider making a pen-and-paper drawing of the functions and how they call each other.
## Part 2: Creating New Stories

In this part, you’ll design and write the functionality to let logged-in users add new stories.

### Subpart 2A: Sending Story Data to the Backend API
- Write a method to add a new story by sending the right data to the API.
- Complete the addStory method in the StoryList class, with the same parameters and results as specified in the comment.
- Test the method by creating a new story in the browser console with the following code:


## How to Run 
```
$ git clone https://github.com/cng008/16_Hack-or-Snooze.git
$ python3 -m http.server
```
