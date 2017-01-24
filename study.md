# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](https://www.mountaingoatsoftware.com/agile/user-stories)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to the following in this file via a pull request:

-   A wireframe of what your game project will look like.
![Wireframes](http://imgur.com/zWCGR3C "Current Wireframe draft")

-   The data structure you plan to use.
```md
In the course of this project I believe it very likely tht I will use at least one instance of all the available data structures within JavaScript, though I will probably be using an array to track the game state.
```
-   How you will take the markup of the game board and represent it in JS
```md
I plan to use a similar method to the js boggle challenge we did early on, that is to say I intend to model the game board as an array of either Xs, Os or empty strings and use a similar mapping method to check for a winner
```
-   How you plan to approach this project.
```md
I will first make a very basic version of the webpage, i.e. the html and css framework. Once that is done and I can interact with something reasonably close to what the final project's DOM will look like I will work on implementing the game logic and authentication concerns.
```
-   4-8 user stories for your game project.
```md
As a player, I would like to be able to log in to the game with a user and password I have created.

As a player, I would like to be able to see my game history, including how many games I have won, in my account.

As a player, I would like to be able to click a square and have it register as "mine".

As a player, I would like to see visually when I have won or lost a game, and have the game board reset.

As a player, I want to play with friends on other devices so that we don't have to sit at one keyboard.
```
-   How you plan to keep your code modular.
```md
Wherever possible I will split code off into logically divided files and only require those files when they are being used.
```
-   What creative spin will you add to your project?
```md
If possible I plan to implement a game history log, as a precursor and part of the chatr log challenge
```
-   How will you use version control to backup / track your project?
```md
Using github and branching off development of each individual feature as appropriate.
```
-   Do you plan to attempt any of the bonuses?
```md
I plan to attempt as many of the bonuses as time allows. Particularly I am interested in attempting the chat log functionality.
```

You may want to submit pictures for your wireframes and/or user stories.
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
has instructions to link to a picture you've uploaded to a service like [Imgur]
(http://imgur.com/).
