
Lesson 5 truth or dare lesson
===============================

create a love meter with the @boardname@.

Topic
-----

If (Conditionals)

Quick Links
-----------
.. toctree::
   :maxdepth: 4

   ./truth-or-dare/activity
   ./truth-or-dare/tutorial
   ./truth-or-dare/challenges
   ./truth-or-dare/quiz
   ./truth-or-dare/quiz-answer




Prior learning/place of lesson in scheme of work
------------------------------------------------

Learn how to use an if statement to run code run code depending on whether a condition is true or not. We will be learning how to create the game truth or dare using input an if statement, a local variable, math random as well as simple commands, such as show string and show LEDs.

Documentation
-------------

.. code-block:: cards

   basic.showLeds(`
       . . . . .
       . . . . .
       . . # . .
       . . . . .
       . . . . .
       `)
   input.onButtonPressed(Button.A, () => {})
   let x = 0
   Math.randomRange(0, 3)
   if (true) {}
   basic.showString("Hello!")

Objectives
----------


* learn how to display an image on the @boardname@
* learn how to run code when an input button is pressed
* learn how to a create a variable for a place where you can store and retrieve data
* learn how to declare a new local variable or update the value of a variable
* learn how to return a random number
* learn how to conditionally run code depending on whether a condition is true or not
* learn how to show a string on the LED screen one character at a time (scrolling from left to right)
