# X-Team 06 Project Proposal

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

A maintaince shop needs to be able to track the tools that its mechanics use. The shop needs to be able to keep track of multiple of the same type of tool and allow workers to check them in and out.

A program that would help solve this organization problem would need to have a way to lookup, check in/out, insert, and remove tools. Since there are multiples of each type of tool there needs to be a way to keep track of how many of each item there are.

## Questions to answer for Exercise #2

1. Name: Madison Mechanics Catalog


2. Output: Describe the output your program will produce.  Include and example format of the output produced.

The program will produce search results that will show the status of a tool. The status will include how many items are in stock and a description of when the tool was checked out.

*Example*
tool: wrench  
number-in-stock: 7 out of 10  
last checked out: 1:01 PM  
List of wrenches:  
Wrench1    IN  
Wrench2    OUT  
... Continued  

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

The entire catalog needs to be added in order for the program to be able to provide useful results. It also requires users to input new items as they come in. It will also need to be able to take search inputs from the user. The users will also need to input data for items that need to be removed.

*Examples*  
**search**  
item id or name:  
  
**insert**  
item id:  
description:  
  
**remove**  
item id:  
description:  
  
**toggleInOut**  
This method would check in or out a tool.  
item id:  
  

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.  
  
Text menus would be best for this interface. A GUI would not give a further advantage.  
  
Example:  
5 Tools Checked Out  
S to search  
C to check in/out a tool  
Search: Hammer  
2 out of 3 Hammers available:  
Hammer1    Out  
Hammer2    IN  
Hammer3    IN  

  
5. Types List: Break your solution idea down into units that you think can be implemented with a single class.  
ToolHashTable  
ToolHashTableADT  
Menu User Interface (Main.java)  


Name each interface or class and briefly describe its function or purpose.


## Edit and Submit this file and any figures referenced by this document.

