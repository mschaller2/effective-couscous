# X-Team 30 Project Proposal

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Briefly describe a problem that your team would like to solve.  
Describe at a high level a program that could solve that problem.

College students have a hard time budgeting, but also seem to have the most expansive and maybe expensive appetites at times. There’s a lot of cheap options around campus, but if you go out to eat too much, it can add up quickly; on the other hand, if you don’t go out often, it can still be expensive to go out to a fancy place even once in a while. We thought about solving this problem by creating a program that can keep track of both your budget as well as storing different restaurants and their prices. Each restaurant could have an associated average price, you could change the cost based on how many people are eating there, and you could also have a balance-sheet of sorts that keeps track of recent ins and outs of a given amount of money. 
Some testing would include making sure that the average budget estimates are appropriately calculated, that the data is being accessed with the proper efficiency, that the restaurant structure is behaving properly, and that the User class is keeping track of all of its respective data. 

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)



2. Output: Describe the output your program will produce.  Include and example format of the output produced.



3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.



4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.



5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

Types include a Restaurant class and a User class primarily. Using two classes would keep things simple and most of the data should fit in these classes, especially since a lot of the sample output would be based on simple calculations based on the data at hand.
Restaurant class: Stores location, average price of a meal
User class: stores financial information (current amt, a few recent transactions?) 
A way to retrieve this data could be using a custom hash table that stores Restaurants and Users, since that way, information could be interacted with quickly.


Name each interface or class and briefly describe its function or purpose.


## Edit and Submit this file and any figures referenced by this document.

