# Roadmap Topic Breakdown

## 

**Topic: SQL/SQLAlchemy**

**Module: SQL/SQLAlchemy**

_**Learning Objectives:**_

* Students will learn the basics of SQL, its purpose, and how it is different from NoSQL.
* Students will learn how to use SQLAlchemy to easily implement an SQL database into their Flask applications.
* Students will learn how to interact with their SQL database through querying objects, deleting objects, etc..
* Students will learn how to make models and use Flask-Marshmallow to specify the required format of each field.
* Students will learn the concept of ORM with SQL.

_**Activities:**_

* Countries Database
  * Students will create a simple POST endpoint that will add and commit information about a country to a db session and a PUT endpoint that can query and edit the information in the db and commit.
* Classroom Directory
  * Students will make a simple Flask application and use SQLAlchemy to build a database of students in a particular classroom. There should be POST and DELETE endpoints.
* Building a School
  * As an extension of the previous activity, now students will use Flask and Flask-Marshmallow to build out different models for a Student, Teacher, Principle, Janitor, Administrator, etc.
* Housing Directory:
  * Now that the student has a school directory, they should create a directory that contains all the information about each person at the school’s housing information; the databases should then be related.

_**Labs:**_

* Flask Election App:
  * Students should make a simple Flask App that is capable of storing information about different candidates in an election. This application must support the CRUD operations and students will use models and Flask-Marshmallow to specify the type of data being stored.
* Recipe Application:
  * Students will alter the recipe application they built in the Flask module to now  use a SQLAlchemy database rather than a native dictionary. This application will require the student to query the database, create Flask-Marshmallow models, and implement the CRUD operations.

## Topic: Python

**Module: Intermediate Python**

_**Learning Objectives**_

* Students will continue applying their fundamental Python skills learned from the previous module.
* Students will begin learning about how to integrate basic data structures like lists and dictionaries to add complexity to their Python code.
* Students will learn how they can use for/while loops and if statements to control the flow of their code.
* Students will learn how to represent strings in Python using F-strings.

_**Activities**_

* Bookkeeper
  * You will write a program that reads and parses a list of Dewey decimal numbers and match it to the correct genre based on the number and then find the distribution of each genre.
* Creating a Menu
  * You will write a simple menu program which prints a menu and behaves according to user input.
* Message Cipher
  * Encode user input with both a Caesar Cipher and a Symmetric Cipher.

_**Labs**_

* Word Translation Calculator
  * You are going to write a program that calculates how often a word appears in a given string.
* Basic Calculator
  * Create a functional calculator in python that can do simple arithmetic operations on two numbers.
* Tic-Tac-Toe
  * Write a Tic-Tac-Toe game, and you will play against an AI which chooses random moves.

