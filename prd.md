# Final Project

Product Requirement Document (PRD)

* [Overview](#overview)
    + [Wordle Game](#wordle-game)
* [Requirements](#requirements)
* [Features/User Stories](#features-user-stories)
    + [The Form](#the-form)
    + [Interactions](#interactions)
    + [Reactify](#reactify)
    + [Layout](#layout)
    + [Game Logic On Single Line](#game-logic-on-single-line)
    + [UI Testing](#ui-testing)
    + [Full Front End Game Logic](#full-front-end-game-logic)
    + [Users](#users)

## Overview

This document describes a “Wordle” game development in order to participate in a full cycle of web development.

The project was structured to support and guide our web development study path.

### Wordle Game

Wordle is a Bull & Cows style word game. The user is required to guess a randomly selected word in N turns. The
application gets each guess as input and provides clues for the next guess.

An example to a “Wordle” game:

* [Hebrew version - Haaretz](https://www.haaretz.co.il/riddles/ty-page/haaretz-wordle)
* [English version - NYT](https://www.nytimes.com/games/wordle/index.html)

## Requirements

Till another decision - Typescript and javascript are allowed.

    We use user stories to describe our application requirements. Each user story contains a list of tasks required to complete it.
    There are several ways to write user stories. I chose a template that describes the product from the point of view of a user who tries to use the application.

| Requirement                                                           | Category          | Target            |
|-----------------------------------------------------------------------|-------------------|-------------------|
| Milestone A                                                           |                   |                   | 
| [Navigating to the page will display a static wordle game](#the-form) | npm, HTML, CSS    | :computer:        | 
| [Navigating to the page will display a static wordle game](#the-form) | npm, HTML, CSS    | :computer:        | 
| [The user should be able to enter a word](#interactions)              | HTML, CSS, JS     | :computer:        | 
| [The user should not notify we changed the implementation](#reactify) | Static React      | :computer: :herb: |                                                          
| Milestone B                                                           |                   |                   | 
| [User should start with welcome and have some help](#layout)          | Routing, Modal    | :computer: :herb: | 
| [User can play](#full-front-end-game-logic)                           | State             | :computer: :herb: | 
| [Let me connect](#users)                                              | Forms and storage | :computer: :herb: | 
| Milestone C                                                           |                   |                   |
| [Let the server choose the word](#choose-word)                        | Express           | :factory: :herb:  |

* :computer: Client Side
* :herb: React
* :factory: Server Side

## Features/User Stories

### The Form

Navigating to the page will display a static “Wordle” game.

* [x] Prepare your development environment
* [x] Implement game HTML page (see example below)
* [x] Add style to the page (choose your own)

![Mock ](docs/wordle-mock.png)

### Interactions

* [x] After page loaded, the focus should be at the first input
* [x] Allow user to enter single letter:
    - Only letters
    - Move focus to the next input in the same row
    - After the last letter show dialog “done”

### Reactify

* [ ] Split the page into components
* [ ] Refactor the page into static React components
    - Consider use the React [tools](https://beta.reactjs.org/learn/start-a-new-react-project)
    - Provide "start" script to run the project (`npm start` to run your project)

### Layout

* [ ] Welcome screen
    * First navigating to the game will the display the welcome
    * The screen should contain the text "Welcome user!"
    * You should choose how to style this page (animation, video, just text)
* [ ] Topbar
    * Should contain header/name and a link/button to display the help screen
* [ ] Help screen
    * Should be [modal popup](https://en.wikipedia.org/wiki/Modal_window)
    * Should close only by clicking X at the top corner or clicking "ESC" in the keyboard
    * You should choose how to explain the game

#### Layout Examples

Welcome Screen

<img src="https://github.com/grunitech/final-project/blob/main/docs/wordle-mock-welcome.png" width="30">

<img src="https://github.com/grunitech/final-project/blob/main/docs/wordle-mock-welcome.png" style="width: 100px">


![Welcome Screen](./docs/wordle-mock-welcome.png)

Top Bar

![Top Bar](./docs/wordle-mock-topbar.png)

### Game Logic On Single Line

* [ ] Choose word (static)
* [ ] Starting at the first line
* [ ] After the last letter check the input against the select word and mark the inputs
    * Bull => green background
    * Cow => yellow background
* [ ] Mark all guessed letters in the virtual keyboard
* [ ] If all letters are Bull display dialog "success"

### UI Testing

TBD

### Full Front End Game Logic

* [ ] For all lines
    * [ ] After finish line logic, put the focus on the first character of the next line
    * [ ] Do single line logic
* [ ] If no success, display dialog "fail"

### Users

* [ ] login link/button at the topbar
    * [ ] Show modal with login form (name) and login button that close the modal
    * [ ] Keep the username locally (browser)
* [ ] Change the welcome screen to greet the user by his name if any, else use "guest"
* [ ] After login, the topbar should contain the username and a logout link/button
* [ ] The logout link/button should delete username locally

### Choose Word

TBD

---

:globe_with_meridians: 
