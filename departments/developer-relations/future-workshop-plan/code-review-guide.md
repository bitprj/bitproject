# Code Review Guide

## **Guide on how to code review**

**Why, what and when to do code reviews?**

It is important to understand **why** we are doing code reviews, while programming it is very easy to type out bugs due to the fast implementation and abstract thinking. Therefore, passing our code through a process of code reviews can lead to a consistent, legible code and also remove accidental errors made.

**What?**  
For your projects you will be dividing your architecture into independent parts before integrating them into a functioning application. Therefore, it in necessary to be able to execute independent portions step by step for example in web development, we must be able to make sure our server is running an functional which is the first step, the second test will be testing the functioning of the web framework that we use \(e.g Flask or Django\).

**When?**  
Code reviews should be conducted before merging into the main branch and after all automatic checks \(tests, styles, other CI\).

While students are conducting code reviews, they should keep the following points in mind:

* Is the system design interlinked?
* Are there any independent tests than be conducted to verify components of the system architecture?

