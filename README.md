Instructions
------------
* Challenge time: Friday, the entire day + the weekend if you need it

Task 
----

Your task is to provide a _Rock, Paper, Scissors_ game for them so they can play on the web with the following user stories:

```sh
As a marketeer
So that I can see my name in lights
I would like to register my name before playing an online game

As a marketeer
So that I can enjoy myself away from the daily grind
I would like to be able to play rock/paper/scissors
```

Hints on functionality

- the marketeer should be able to enter their name before the game
- the marketeer will be presented the choices (rock, paper and scissors)
- the marketeer can choose one option
- the game will choose a random option
- a winner will be declared

## Bonus level 1: Multiplayer

Change the game so that two marketeers can play against each other ( _yes there are two of them_ ).

## Bonus level 2: Rock, Paper, Scissors, Spock, Lizard

Use the _special_ rules ( _you can find them here http://en.wikipedia.org/wiki/Rock-paper-scissors-lizard-Spock_ )


Usage
-----

Clone this repo to your local machine

Run Bundler to install Gems: bundle

Navigate to the root directory in the terminal and start the server: ruby app.rb

Take a note of the port number and navigate to http://localhost:port_number in your browser.


Testing
-------

To run the unit and feature tests for RPS-challenge, please navigate to the root directory of the project and run: rspec


To Do
-----

Need to add HTML and CSS.


Technologies used
-----------------

Ruby
Sinatra
TDD (via RSpec and Capybara)

