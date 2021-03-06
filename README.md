![header](https://capsule-render.vercel.app/api?type=slice&color=auto&height=130&section=header&text=HANGMAN%20game&fontSize=30&fontAlign=80)
<img src="Screenshot.jpg" width="400px">

# Hangman-Game
Classical Hangman Game written in HTML, CSS, JS
in one compact index.html file

![](Screen.gif)

## Features:
* Word for quessing
* Inputfield with 'Submit'(OK) button
* 'Enter' key keypress(as submit) to play the game
* Guessed characters in alphabetical order
* Number of possible wrong quesses left
* Points calculation system(max 100 points)
* 'New Game' button
* Hidden(at the beginning) 'Solution' field with button 
* When game is lost, guessing input will be removed from UI
* Rotating, re-sizing and color changing canvas with hangman drawing
* Points textbox field background color depending on points: red -> green
* Hover on labes - zoom in effect
* Hover on canvas - zoom in and canvas background color change
* Hover on text output fields - text fields background color change
* Hover on small triangle on left bottom corner - rotate screen back and forth
* Tooltip - when hovering over 'HANGMAN' title
* Tooltip - when hovering over text input field
* Click on canvas to save it as an image

## Calculating points:
* Maximum for the game is 100 points.
* Minimum can be 0 points(calculation will never go below 0 points).
* At the beginning of the game every right letter is worth 10 points.
* Every wrong letter devaluates the 10 points value for the right letters by 1 point and 1 point will be removed from total count.
* By selecting a letter that is already selected, 2 points will be removed from total.
* If player can't guess the word on total moves, the final points count will be divided by 2.

## GOOD LUCK !
![footer](https://capsule-render.vercel.app/api?type=slice&color=auto&height=130&section=footer)
