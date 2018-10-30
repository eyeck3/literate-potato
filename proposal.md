# X-Team 02 Just Horsing Around

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

The UW equestrian team desires a better way to reserve horses and confirm that they are not overworked by the riders. The Horses can only be ridden a certain amount of times a day/week depending on whether the horses are being jumped or flatted(no jumping), and it can be problematic to determine when a horse has exceeded it's healthy limit for the week. The riders need to reserve horses for certain times and activity, and the program must not allow users to use a horse if it has already been ridden to it's quota for that activity. This app will also make sure that each horse recieves routine excercise, and is not over worked.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

JustHorsingAround


2. Output: Describe the output your program will produce.  Include and example format of the output produced.

The program will tell you when a horse will be available or what horses are available on a given day. Users of the program can check a horse's status


3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.


Date of use: date the user would like to request to use the horse<br/>
Horse name: name of the horse the user would like use of<br/>
Jumping or Flatting: if the user would like to jump or flat the horse<br/>

ex:<br/>
display:"Enter date:" enter:"10/29/2018"<br/>
display:"Enter horse name:" enter:"Hudson"<br/>
display: buttons- "Jumping", "Flatting"<br/>

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

See next seven days, can pick one. Then, can pick an activity. Can either pick jumping or flatting between two displayed  
buttons. Can then choose between the available horses on that day from a list. User then recieves confirmation that their  
reservation has been confirmed.  

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

Horse Class stores information about the horse and its previous events. Event information contained in a 7 element
boolean array that contains true on days of the week that the horse jumped.
GUI used for selecting a horse to check its information.

Test class that will test different horse reservations and confirm that the correct horses are left availiable. Will also check the schedule remains correct as the days change and that the array resets after the day has passed. This will use junit testing.


## Edit and Submit this file and any figures referenced by this document.

