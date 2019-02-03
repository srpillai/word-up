# word-up
Last assignment for the Front-end Skill Track

Word Up Game


This game you are trying to use is called Word Up!, and it is best described as a cross between Scrabble, Solitaire, and the Hunger Games in Space.

Background

RULES OF THE GAME
* The object of the game is to spell as many words as possible before time runs out, using only the letters specified.
* A word is invalid if it contains any letters that aren't in the specified set of allowed letters.
* A word is also invalid if it turns out not to be a real word.
* Your total score is the sum of the scores of all your valid words.
* The score of each word is the sum of the scores of each of its letters.
* The score of a letter is simply its score from the boardgame Scrabble.
* Unlike in Scrabble, you may use the same letter more than once in a single word.


THE USER INTERFACE
* When the user clicks New Game, the letters are revealed and she can begin typing words.
* The letters are presented as little "chips" (I am going to refer to these things as chips throughout the assignment).
* Each letter chip contains a smaller chip indicating its points value.
* As the user types, the page provides continuous feedback. Specifically, if the word she is currently typing contains any letters that are not allowed, then the disallowed letters appear as red chips underneath the textbox.
* If the user tries to submit (presses Enter after typing) a word that contains disallowed letters, then the textbox simply clears and the word is not submitted.
* Once the user does submit a word containing only valid letters, it appears in a chip below the textbox.
* Shortly after a word chip appears, it will sprout a smaller (blue or red) chip indicating the points total for the word. A normal word will contain a blue chip with a number indicating its score. But a gibberish, nonexistent word will instead contain a red chip with an "X".
* Once the timer runs out, the textbox is no longer usable.

The Pearson Dictionary API

What service do we need from Pearson API for? A dictionary. Our way of checking the validity of the user's word submissions will be to look up each word in the dictionary and see if it exists.


Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

* Download a copy from the Github: https://github.com/srpillai/word-up.git

Prerequisites
What things you need to install the software and how to install them
Give examples

* You will need a chrome or similar browser
* This game assumes that Pearson Dictionary API is available and working

Installing
A step by step series of examples that tell you how to get a development env running
Say what the step will be
Give the example
And repeat
until finished
End with an example of getting some data out of the system or using it for a little demo

**
* Clone or Download a copy from the Github: https://github.com/srpillai/word-up.git
* open the index.html in any browser
**

Built With

* HTML - The web language
* CSS - for styling
* JQuery and Bootstrap - Used for styling also
* Javascript - for interactivity

Contributing

* Created as part of Launchcode unit-3 front-end development course

Authors
* Radhakrishnan Pillai - Initial work - LaunchCoder 2019

License
* This project is licensed under the MIT License 

Acknowledgments
* Launchcode Unit-3 Team
* Inspiration: LC 101 - Launchcode, Kansas City, MO
