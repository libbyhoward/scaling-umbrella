# X-Team 34 Project Proposal - School Seating Chart 

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

A problem that we would like to solve is the issue of making a seating chart in school classrooms. Teachers are left on their own to make these arrangements and often struggle with how to make their classroom compatible. Especially since many students come from different backgrounds.
A program that would solve this problem would generate a seating chart based off of different qualities that students possess. Teachers would have the ability to choose how students are matched together (ex. economic background, ethnicty, gender, grades etc.). The teachers would have personal data about each student that allows them to make these choices about how they are seated. The program will group students in arrangements of rows or tables based on the teachers preferences. 

## Questions to answer for Exercise #2

1. Name: School Seating Chart



2. Output: Describe the output your program will produce.  Include and example format of the output produced.
Seating chart arrangment including table number, the list of students sitting at that table,
Table 1  ->   Student A | Student B | Student C | Student D     
   .
   .
   .
3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.
Student name, gender, ethnicity, math grades/scores, reading grades/scores, personality(loud or quiet), class(Economic).
Example: Joe, Male, Caucasian, 98, 68, Loud, Middle.  




4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

Enter student information below

Name: 
Age: 
Gender: 
Ethnicity: 
Math Score: 
Reading Score: 
Personality (loud or quiet): 
Economic Class: 
Additional Notes: 

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.
Seating Chart Generator:
 create hashTable
 generate table number (w/hash function) of student to sit at (based off of category and student fields)
 rehash if more students added to class

Name each interface or class and briefly describe its function or purpose.

Student Class that contains the information of a student-- with fields 'name', 'gender', etc.
Seating Chart Class that contains the students at each table -- with fields 'table number'
Seating Chart Generator Class that generates the randomized seating chart -- with fields 'class list', 'category' to randomize within

## Edit and Submit this file and any figures referenced by this document.

