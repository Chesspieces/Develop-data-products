Guess a random number
========================================================
author: me  
date: July 31st 2016
autosize: true

Introduction and Motivation Behind the App
========================================================

This shiny app is created as part of the course project for the
Developing Data Products class under the Data Science Specialization offered by Johns Hopkins Bloomberg School of Public Health and Coursera.

How to Play Guess a random Number
========================================================

This game is easy to play 

For the newbie further information on how to play the game is on the game interface itself. 

Basically, the user/player has to guess a number between 1 and 100and see if it matches the computers selection. 
The game outputs feedback to the player and lets him/her know if the guess is higher or lower than the number. Moreover, the game also lets the user know if the guess is below or above the number.

Examples of the computer drawing a random number
========================================================


```r
floor(runif(1,1,101))
```

```
[1] 31
```

```r
floor(runif(1,1,101))
```

```
[1] 61
```

```r
floor(runif(1,1,101))
```

```
[1] 39
```

Remarks
========================================================

-Although I have made some efforts in making the game, please note that it is by no means complete or flawless. I am not an experienced programmer.

-A special thanks to Dr. Caffo for his contribution on the Developing Data Products class. It was due to his instructions and directions that the creation of this game was made possible.
