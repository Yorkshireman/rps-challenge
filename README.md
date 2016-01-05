This was a 'weekend challenge' I completed while at Makers Academy. The spec I was given is shown below. I built it using RSpec and Sinatra and deployed it to Heroku.  Extending the game with the Lizard & Spock variation was fun!  

As you can see, I was provided with User Stories and I built it up from there, initially sketching out the nouns and verbs from the User Stories and using those to guide my class names, class responsibilities and method names.  

To run:  
`git clone git@github.com:Yorkshireman/rps-challenge.git`  
`bundle install`  
`rackup`  
- navigate to [http://localhost:9292](http://localhost:9292) in your browser  

To run the tests:  
`rspec`  

To play online, go [here](https://rockpaperscissors-ruby.herokuapp.com/).

# RPS Challenge

Instructions
-------
* Challenge time: Friday, the entire day + the weekend if you need it
* Feel free to use google, your notes, books, etc but work on your own
* You must submit a pull request to this repo with your code by 9am Monday morning

Task 
----
  
The Makers Academy Marketing Array ( **MAMA** ) have asked us to provide a game for them. Their daily grind is pretty tough and they need time to steam a little.

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


As usual please start by

* Filling out your learning plan self review for the week: https://github.com/makersacademy/learning_plan (if you haven't already)
* Forking this repo
* TEST driving development of your app

## Bonus: Rock, Paper, Scissors, Spock, Lizard

Use the _special_ rules ( _you can find them here http://en.wikipedia.org/wiki/Rock-paper-scissors-lizard-Spock_ )

## Basic Rules

- Rock beats Scissors
- Scissors beats Paper
- Paper beats Rock
