
![Demo of game](https://github.com/diannedejesus/spellinggame/spellinggamedemo.gif)
# The Spelling Game
This application is a spelling practice game aimed at young children.

## How It's Made:

**Tech used:** HTML, CSS, JavaScript

### Description
The game highlights and pronounces the letters displayed under the picture when typed on the keyboard. The letter remains highlighted if typed in the correct sequence. If an incorrect letter is typed or out of sequence the letters are unhighlighted and progress is reset. When the sequence is completed is plays a sound associated to the image and resets the game.

### Initial State
In this initial state the game is waiting for a letter to be typed. It will only recognize one of the letters already displayed.

### Initial Input
In this state, the application is verify the typed key and if it coincides with one of the displayed letters it will react and if not it will not do anything.

It reacts to the correct typed letter (case does not matter) by highlighting the letter with a border (This done by inserting the css class associated with the desired style). It also plays the sound of the letter name.

If the letter typed is not the first letter of the word the game will reset.

### Reset
The game will remove the hightlights off of all letters. It will also reset the progress back to the first letter.

### Sequence Active
If the letter typed is one of the displayed letters thenaa then the game will highlight that letter (if not highlighted), leaving the previously highlighted letter intacted/highlighted and activate the sound that letter. If it is not the next letter it will reset the game, if it is the next letter it will remain highlighted waiting for the next letter to be pressed.

### Complete Sequence
When the last letter of the sequence is clicked appropiately then the last letter is highlighted, the letter is pronounced and after that sound finishes playing another sound is played. This sound is associated to the image and is to celebrate completing the sequence. Once the sound finishes the game is reset.

### User Interface
![Image of interface](https://github.com/diannedejesus/spellinggame/spellinggame.png)
**Title:** Static display of the games name.
**Image:** A visualization of the word to be writtin by the user.
**Letter Squares:** The correct spelling of the word.
**Hightlighted Letter Squares:** Visual guide to let the user know if they have typed the word correctly.

## Future features and optimizations
- Verify if words with repeated letters work properly.
- Include a reaction for when an incorrect letter, that is not displayed.
- Include a reation for when a letter that is out of sequence is typed.
- Include a celebratory visual cue for the correct sequence.
- When a correct sequence is entered the game should either automaticly cycle to a new image or offered a next button.
- A database should be implemented for words and associated information in order to ease the creation/inclusion of new words.
- Possibly create a page for uploading/adding new words, with would check for the requiered information (word, image, associated sound)
- Possibly allow for someone to select a group a words for practice.

## Other projects:
Take a look at these projects that I have:

**To-do App:** https://github.com/diannedejesus/100devs_todo


