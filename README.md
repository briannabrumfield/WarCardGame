# War CardGame
CS 4773 Object Oriented Design - Assignment 2

### Description
In this assignment, you will design and build an object-oriented implementation of 3 variations of the card game, War.
**NO GUI**
The basic rules for the game are located here:
http://www.bicyclecards.com/how-to-play/war/

### Variations to Implement
a. placing won cards on the bottom of the player’s hand (you will need to have a maximum # of iterations because this game variation can last a ridiculously long time). Winner is player with most cards in hand at end of game.
b. placing won cards in a separate points pile. Winner is player with most cards in points pile at end of game.
c. 3-player war placing won cards in a separate points pile. The rules for 3-person war are located here: https://en.wikipedia.org/wiki/War_(card_game). Winner is player with most cards in points pile at end of game.

Game implementations must log gameplay to the console. All 3 variations should allow for the possibility of a tie and output should indicate if a tie occurs.

Code must follow all of the clean code rules as described by Uncle Bob, AS WELL AS:
a. your Java project must have AT LEAST 8 .java files (including Enums but excluding JUnit files)
b. no .java file may be more than 150 lines long (including blank lines and comments)
c. no .java file may be fewer than 3 lines long (including blank lines and comments)
d. error handling can only be accomplished using unchecked exceptions

You are required to *create 10 JUnit test cases* that test game variation outcomes WITH A FIXED DECK. 
This means that your card deck implementation must allow for the traditional 52 cards with a shuffle, as well as manually assigning it a set of known cards (e.g., a 2 card deck, a 3 card deck, a 4 card deck, etc.). 
***If you know the order of the cards in the deck, then you know the expected outcome of the unit tests.***

### SUGGESTED APPROACH:
1. break out the functional requirements and data attributes
2. create a UML class diagram where you assign some of the functions and
attributes for just a few objects and draw relationships between the objects. start
simple: with the cards and the deck
3. implement what you designed in #2
4. create some unit tests for what you did in #3
5. repeat #s 2 through 4 until you have a testable first variation of War
6. now design, build, and test a second variation but be sure to use polymorphism
and share code with the first variation
7. repeat until done

##### Include in Project
Put a PNG or JPG copy of your UML diagram in your Eclipse project and call it
assignment2UML.png or .jpg


|Points| Breakdown|
|:--|:--|
|30 pts | All 3 variations of War execute and output required log messages|
|30 pts | Object-oriented design including use of 4 GRASP and/or SOLID principles and satisfies # of java files and file size requirements and unchecked exceptions for error handling|
|20 pts | Code is readable|
|10 pts |UML class diagram|
|10 pts |At least 10 JUnit test cases and all pass|
