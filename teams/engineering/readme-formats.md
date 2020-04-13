# README Formats

## README Formats

### Topic README Format

#### Github id \(This is required\)

Each topic needs a github\_id so that the server knows it is unique. The word "github\_id" should be in a markdown h1 tag like below:

```text
# github_id
1
```

#### Name \(This is required\)

Each Topic needs a name field. The word "name" should be in markdown h1 tag like below:

```text
# name
Postman Topic
```

#### Description \(This is required\)

Each Topic has a description field to describe what the topic will accomplish. The word "description" should be in markdown h1 tag like below:

```text
# description
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum
```

#### Image \(This is required\)

Each Topic has an image field. The word "image" should be in markdown h1 tag while the image url must be in an img tag:

```text
# image
<img src="images/dee.jpg">
```

#### Image Folder \(This is required\)

Each Topic needs to point to an image folder where the image is being used. The word "image\_folder" should be in a markdown h1 tag like below:

```text
# image_folder
Topic_Postman/
```

#### Modules \(This is not required\)

Each Topic has modules. To add modules to a topic, add the module's github\_ids in a list. Add the word "modules" in a markdown h1 tag and then add the github\_ids in a list with \*'s:

```text
# modules
* 5
```

#### Topic README Example

```text
# github_id
1

# name
Postman Topic

# description
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum  

# image
<img src="images/dee.jpg">

# image_folder
Topic_Postman/

# modules
* 5
```

### Module README Format

#### Github id \(This is required\)

Each module needs a github\_id so that the server knows it is unique. The word "github\_id" should be in a markdown h1 tag like below:

```text
# github_id
1
```

#### Name \(This is required\)

Each Module needs a name field. The word "name" should be in markdown h1 tag like below:

```text
# name
Some Module 2
```

#### Description \(This is required\)

Each Module has a description field to describe what the module will accomplish. The word "description" should be in markdown h1 tag like below:

```text
# description
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum
```

#### Gems\_needed \(This is required\)

Each Module has a gems\_needed field which is the number of gems needed to complete this module. The word "gems\_needed" should be in markdown h1 tag like below:

**Note: Set it as 0 for now**

```text
# gems_needed
0
```

#### Image \(This is required\)

Each Module has an image field. The word "image" should be in markdown h1 tag while the image url should be put in an img tag:

```text
# image
<img src="images/dee.jpg">
```

#### Image Folder \(This is required\)

Each Module needs to point to an image folder where the image is being used. The word "image\_folder" should be in a markdown h1 tag like below:

```text
# image_folder
Topic_1/Module2_test/
```

#### Final Example

```text
# github_id
1

# name
Some Module 2

# description
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum  

# gems_needed
    0

# image
<img src="images/dee.jpg">

# image_folder
Topic_1/Module2_test/
```

### Activity/Lab README Format

#### Github id \(This is required\)

Each activity needs a github\_id so that the server knows it is unique. The word "github\_id" should be in a markdown h1 tag like below:

```text
# github_id
1
```

#### Name \(This is required\)

Each Activity/Lab needs a name field. The word "name" should be in markdown h1 tag like below:

```text
# name
Some Activity
```

#### Description \(This is required\)

Each Activity/Lab has a description field to describe what the activity will accomplish. The word "description" should be in markdown h1 tag like below:

```text
# description
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip.
```

#### Summary \(This is required\)

Each Activity/Lab has a summary field to describe what the activity will accomplish in depth. The word "summary" should be in markdown h1 tag like below:

```text
# summary
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum
```

#### Difficulty \(This is required\)

Each Activity/Lab needs a Difficulty field to indicate how hard the Activity/Lab is for the user. Add the "word" difficulty in a markdown h1 tag, and put the difficulty under it:

Types of Difficulty:

* Hard
* Medium
* Easy

```text
# difficulty
Hard
```

#### Image \(This is required\)

Each Activity has an image field. The word "image" should be in markdown h1 tag like below:

```text
# image
<img src="images/bandanna.jpg">
```

#### Image Folder \(This is required\)

Each Activity needs to point to an image folder where the image is being used. The word "image\_folder" should be in a markdown h1 tag like below:

```text
# image_folder
Topic1/Module2_test/Activity_4/
```

#### Cards

The cards fields is used to indicate the name of the card, order in which the card is shown and number of gems that the card has.

**Cards \(This is required\)**

To define cards in an Activity, you have to have the word "cards" in a markdown h1 tag. This is used to tell the server where the cards are:

```text
# cards
```

**Card Key \(This is required\)**

Each card you define in the Activity README, must have a corresponding filename as its key. For example if a card/hint was named [1.md](http://1.md) then its key would be 1. The card key must be placed in a markdown h2 tag like below:

```text
## 1
```

**Card Name \(This is required\)**

Each card has a name field. Each name should be in a markdown h3 tag like below:

```text
### name
Card 1 Github
```

**Card Order \(This is required\)**

Each card has an order field. The order is the last digit of the card key. If a card had a key of 1-2, then the order for that card would be 2. The order of a card is the order in which each card is displayed. Each name should be in a markdown h3 tag like below:

```text
### order
2
```

**Card Gems \(This is required\)**

Each card has a gems field. The gems fields is used to indicate the number of gems earned when opening a card. If this for a medium/easy card, this field is for the amount of gems a student would lose for using the medium/easy card. Each name should be in a markdown h3 tag like below:

```text
### gems
300
```

**Card Concepts \(Concepts only apply to hard cards, not medium or easy cards\)**

**Note: This fields is NOT required for the Activity README.md**

To give a card concepts, write the word "concepts" in a markdown h3 tag and list out the name of the concepts in \* like below:

```text
### concepts
* concept_1.md
* concept_2.md
```

**Note: When defining the cards, please put them in order of difficulty. Hard cards should be defined first, Medium cards next, and last easy cards. Below is an example:**

```text
# cards

## 1

### name
Bleh Card 1 Github

### order
1 

### gems
300

### concepts
* concept_1.md
* concept_2.md

## 2

### name
Bleh Card 2 Github

### order
2

### gems
300

## 1-1

### name
Bleh Card 2 Github

### order
1

### gems
300

## 2-1

### name
Bleh Card 4 Github

### order
1

### gems
300

## 1-1-1

### name
Bleh Card 3 Github

### order
1

### gems
300

## 1-2-1

### name
Bleh Card 4 Github

### order
1

### gems
300

## 2-1-1

### name
Bleh Card 131 Github

### order
1

### gems
300
```

#### Final Example

```text
# github_id
19

# name
Some Activity

# description
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip.

# summary
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum 

# difficulty
Hard

# image
<img src="images/bandanna.jpg">

# image_folder
Topic1/Module2_test/Activity_4/

# cards

## 1

### name
Card 1 Github

### order
2

### gems
300

## 1-1

### name
Medium Card

### order
1

### gems
100
```

### Hint Format \(Medium/Easy Card\)

#### Image Folder \(This is required\)

Each Hint \(easy or medium card\) needs to point to an image folder where the image is being used. The word "image\_folder" should be in a markdown h1 tag like below:

```text
# image_folder
Topic1/Module2_test/Activity_7/cards
```

#### Start of the Steps

You must include the word "steps" in a markdown h1 tag so the sever knows when the steps start like below:

```text
# steps
```

#### Step Key \(This is required\)

Next you **must** include the step key so the server can keep track of the steps. The Step key should be the hint name along with the step number in a markdown h1 tag like this:

```text
## 1-2-1 Step 1
```

#### Step name \(This is required\)

Under the hint name, you have to give the step a name with a markdown h2 tag. **Please put the contents of name in a code block.** It should look something like this:

```text
### name
```

How to install VSCode

```text

```

#### Md\_content \(This is required\)

To include the md\_content for the step, give the md\_content with a markdown h2 tag. **Please put the contents of md\_content in a code block.** It should look something like this:

```text
### md_content
```

### Hello world in js

This is how you do it

```text

```

#### Optional Fields

#### Code Snippet

To include the code snippet for the step, give the code snippet with a markdown h2 tag. **Please put the contents of the code in a code block.** It should look something like this:

```text
### code_snippet
```

def pls\_work\(\): return True... maybe

```text

```

#### Image

To include an image for a step, you need to put a h2 markdown tag and assign it to "image"

```text
### image
<img src="images/bandanna.jpg">
```

#### Final Example:

Note: You can always add more steps as long as you follow the above syntax.

```text
# image_folder
Topic1/Module2_test/Activity_7/cards

# steps

## 1-2-1 Step 1

### name
How to install VSCode

### md_content
```

Hello world in js This is how you do it

```text
### code_snippet
```

def pls\_work\(\): return True... maybe

```text
### image
<img src="images/bandanna.jpg">
```

### Concept Format

#### Concept Name \(This is required\)

Each concept needs a name. The name should be in a h1 tag like below:

```text
# concept_name
Concept name
```

#### Image Folder \(This is required\)

Each Concept needs to point to an image folder where the image is being used. The image\_folder should be in a markdown h1 tag like below:

```text
# image_folder
Topic1/Module2_test/concepts/
```

#### Step Key \(This is required\)

Next you **must** include the step key so the server can keep track of the steps. The Step key should be the concept name along with the step number in a markdown h1 tag like this:

```text
# concept_name Step 1
```

#### Step name \(This is required\)

Under the hint name, you have to give the step a name with a markdown h2 tag. **Please put the contents of name in a code block.** It should look something like this:

```text
## name
```

How to install VSCode

```text

```

#### Md\_content \(You need to include this for each step\)

To include the md\_content for the step, give the md\_content with a markdown h2 tag. **Please put the contents of md\_content in a code block.** It should look something like this:

```text
## md_content
```
Hello world in js
This is how you do it
```
```

#### Optional Fields

#### Code Snippet

To include the code snippet for the step, give the code snippet with a markdown h2 tag. **Please put the contents of the code in a code block.** It should look something like this:

```text
## code_snippet
```
def pls_work(): return True... maybe
```
```

#### Image

To include an image for a step, you need to put a h2 markdown tag and assign it to "image"

```text
## image
<img src="dee.jpg">
```

#### Final Example:

Note: You can always add more steps as long as you follow the above syntax.

```text
# concept_name
Concept name

# image_folder
Topic1/Module2_test/concepts/

# 1-2-1 Step 1

## name
```

How to install VSCode

```text
## md_content
```

Hello world in js This is how you do it

```text
## code_snippet
```

def pls\_work\(\): return True... maybe

```text
## image
<img src="dee.jpg">
```

### Checkpoint Format

#### Name of the file

For the file name, name it the card that you want it to be associated with. So if you wanted to create a checkpoint for [1.md](http://1.md), you would name the checkpoint file "[1-checkpoint.md](http://1-checkpoint.md)"

#### Name \(This is required\)

This is the name of the checkpoint. Put the word "name" in a markdown h1 tag. Put the name of the checkpoint under the h1 tag like so:

```text
# name
Code Check in
```

#### Cards Folder \(This is required\)

This is the folder on where the cards are located. Put the word "cards\_folder" in a markdown h1 tag. Put the card folder path under the h1 tag like so:

```text
# cards_folder
Topic1/Module7/Activity_13/cards/
```

#### Checkpoint Type \(This is required\)

This is to define the type of checkpoint. Put the word checkpoint\_type in a markdown h1 tag.

Checkpoints could be **ONE** of the following:

* Video
* Image
* Short Answer
* Multiple Choice
* Autograder

```text
# checkpoint_type
Video
```

#### Instruction \(This is required\)

This is what you would tell the user to do for a checkpoint. Put the word instruction in a markdown h1 tag. Put the instruction content under the h1 tag like so:

```text
# instruction
Submit a photo your Minsweeper code working
```

#### Other Fields

#### Criteria \(This is required for Video and Image Checkpoints\)

Criteria is a rubric for TA's to grade a student's Image or Video Checkpoint.

You must declare where the criteria for a checkpoint would begin. You would do this by putting the word "criteria" in a markdown h1 tag like so:

```text
# criteria
```

After that you can list each criteria in a markdown h2 tag with a number at the end like so:

```text
## criteria_1
Does the student's board look like this:
```

#### Multiple Choice \(This is required for Multiple Choice Checkpoints\)

You must declare where the choices for the checkpoint would begin. You would do this by putting the words mc\_choices in a markdown h1 tag like so:

```text
# mc_choices
```

Next you would define each choice in a markdown h2 tag with a number at the end like so:

```text
## choice_1
```

#### Files to send \(This is required for Autograder Checkpoint\)

These are the files that the student will submit if the student chooses to submit through their code to the cli.

```text
# files_to_send
main.py class1.py class2.py
```

#### Test file location \(This is required for Autograder Checkpoint\)

This field is used to tell where the test case folder is for the checkpoint.

```text
# test_file_location
Topic1/Module7/Activity_13/Tests/test_1
```

### 

#### Solution \(This is required for Short Answer Checkpoints\)

This field is used to give a sample answer for a Short Answer Checkpoint

```text
# solution
Some Solution
```

### Checkpoint Examples

#### Video/Image

```text
# name
Code Check in

# cards_folder
Topic1/Module7/Activity_13/Cards/

# checkpoint_type
Video

# instruction
Submit a photo your Minsweeper code working

# criteria

## criteria_1
Does the student's board look like this?

## criteria_2
Does the student's code print the board out?
```

#### Short Answer

```text
# name
Print Statements Short Answer

# cards_folder
Topic1/Module7/Activity_13/Cards/

# checkpoint_type
Short Answer

# instruction
Submit a photo your Minsweeper code working

# solution
Some solution
```

#### Multiple Choice

```text
# name
Print Statement Multiple Choice

# cards_folder
Topic1/Module7/Activity_13/Cards/

# checkpoint_type
Multiple Choice

# instruction
Which of the following choices is the correct way to use a print statement in python

# mc_choices

## choice_1
console.log()

## choice_2
print()

## choice_3
printf()

# correct_choice
print()
```

#### Autograder

```text
# name
Autograder Checkpoint  

# cards_folder
Topic1/Module7/Activity_13/Cards/

# checkpoint_type
Autograder

# instruction
Do this     

# files_to_send
main.py class1.py class2.py

# test_file_location
Topic1/Module7/Activity_13/Tests/test_1
```

### Test Cases Format

**Note: All test case files must end with .test**

#### File formating

If you have multiple test cases they should have a number at the end of it like below:

**Your test case must be named after the lab/activity and then a sequential number**

* minesweeper1.test
* minesweeper2.test
* minesweeper3.test

If you have input files, then make sure that their name as .txt. **They should be in numerical order as like this**:

* input1.txt
* input2.txt
* input3.txt

#### Name

Each test case file must have a name on the first line like so:

```text
Board Function
>>> main(2)
Mines: 10
  0123456789
0 XXXXXXXXXX 0
1 XXXXXXXXXX 1
2 XXXXXXXXXX 2
3 XXXXXXXXXX 3
4 XXXXXXXXXX 4
5 XXXXXXXXXX 5
6 XXXXXXXXXX 6
7 XXXXXXXXXX 7
8 XXXXXXXXXX 8
9 XXXXXXXXXX 9
  0123456789
Enter your move (for help enter "H"): 42
Mines: 10
  0123456789
0 XXXXXXXXXX 0
1 XXXXXXXXXX 1
2 XXXXMXXXXX 2
3 XXXXXXXXXX 3
4 XXXXXXXXXX 4
5 XXXXXXXXXX 5
6 XXXXXXXXXX 6
7 XXXXXXXXXX 7
8 XXXXXXXXXX 8
9 XXXXXXXXXX 9
  0123456789
Uh oh! You blew up!
```

#### Inputs

To write test cases, you must type "&gt;&gt;&gt;" followed by the name of the function that you wish to test on. Since you will mostly be testing the main function it would look like the following:

```text
>>> main()
```

#### Outputs

Right after the declaring the function that you want to test, you would put the output right below it like so:

```text
>>> main()
Hello World!
```

#### Handling User Input

If your program needs user input, then you must include the following Python file

[https://gist.github.com/wongband/597c126217a306ca4770931680417faa](https://gist.github.com/wongband/597c126217a306ca4770931680417faa)

For the input.txt files add the input that want to put for the corresponding test file. For example, if you have input1.txt then that should correspond as the input for minesweeper1.test.

Since the minesweeper1.test lab needs to have the input of 42, all we have to do is create an input1.txt with 42 in it. **Do not put a new line if your program does not output a newline.**

```text
42
```

#### Minesweeper Example

Below is the minesweeper1.test file. In this case we target the main function while passing the number 2 to it. Below that function, the output is the board and a prompt for the user input.

```text
Create Board Function
>>> main(2)
Mines: 10
  0123456789
0 XXXXXXXXXX 0
1 XXXXXXXXXX 1
2 XXXXXXXXXX 2
3 XXXXXXXXXX 3
4 XXXXXXXXXX 4
5 XXXXXXXXXX 5
6 XXXXXXXXXX 6
7 XXXXXXXXXX 7
8 XXXXXXXXXX 8
9 XXXXXXXXXX 9
  0123456789
Enter your move (for help enter "H"): 42
Mines: 10
  0123456789
0 XXXXXXXXXX 0
1 XXXXXXXXXX 1
2 XXXXMXXXXX 2
3 XXXXXXXXXX 3
4 XXXXXXXXXX 4
5 XXXXXXXXXX 5
6 XXXXXXXXXX 6
7 XXXXXXXXXX 7
8 XXXXXXXXXX 8
9 XXXXXXXXXX 9
  0123456789
Uh oh! You blew up!
```

