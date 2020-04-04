# Guide to Being a Manager

Reviewers are in charge of **curriculum teams.** Each team consists of 4-6 people who work on different modules of curriculum. They will be tasked with a project, usually covering a topic, and a deadline. By this deadline, all activities, labs and workshops for that project should be completed.

## Starting Off: Receiving Module Assignments

All reviewers will be assigned an issue in the **bitproject** repository, to be completed within _3 days of assignment._

### Pre-approval Checklist

* [ ] Confirm modules to be done
* [ ] Finalize activities, labs and workshop list
* [ ] Confirm overall project deadline

### Post-approval Checklist

* [ ] Making Epics in a Project \[THIS SHOULD BE DONE ASAP post-approval\]
  * [ ] If applicable, make modules as Epics on Zenhub
  * [ ] Post activities, labs and workshops on Zenhub as Epics under the appropriate module
* [ ] First week's issues \[THIS SHOULD BE DONE ASAP post-approval\]
  * [ ] Generate issues that should be completed in the first week
  * [ ] Assign to a milestone for the team
  * [ ] Inform team that their milestone is ready and that it is due in a week
* [ ] Have long-term, week-by-week plan under each activity/lab/workshop Epic describing what should be done by the team each week
* [ ] Generate all issues for all weeks 
  * [ ] Make sure each issue is added to the appropriate Epic
* [ ] Assign Epic Points to each module, activity, lab and workshop
* [ ] Set timeline for module, activity, lab and workshop Epics in Zenhub Calendar

This checklist will be posted within the issue and should all be completed within 3 days of assignment.

## Weekly Manager Checklist

* [ ] Review developers' work and provide a review according to the Pull Request Checklist 
* [ ] Ensure "first draft" pull requests are in **by Friday**
* [ ] "Final draft" pull request to `master` should be in by **Sunday**
* [ ] Generate issues for the project based on feedback received and progress made the week prior
  * [ ] Ensure issues are made and set-up for next week's tasks 
  * [ ] Designate two issues _not being solved_ to be "first timer only" issues
  * [ ] Milestone should be set-up
* [ ] Adjust long-term plan and epic points for each module epic based on feedback and progress
  * [ ] Ensure General Review Checklist is being updated based on the developers' progress
* [ ] Adjust timeline in Zenhub Calendar

## Pull Request Checklist

Every week, there are a couple essential things that every manager should take care in pull requests. This checklist applies to both pull requests from developers' branches to managers' branches and from managers' branches to `master`.

* [ ] **Branch updated from `master`**
* [ ] Spelling and grammar errors fixed
* [ ] Correct Markdown Formatting
* [ ] Adjust timeline in Zenhub Calendar
* [ ] Correctly spaced code snippets
* [ ] Code style followed
* [ ] Local images with &lt;img&gt; NOT Markdown 
* [ ] Splitting Up Cards \(no more than one scroll a card\)
* [ ] Readability Test: Automated Readability Index result of _9th grade or under_ \([https://readabilityformulas.com/free-readability-formula-tests.php](https://readabilityformulas.com/free-readability-formula-tests.php)\)
* [ ] Visuals make sense
  * [ ] Alternate text for visuals
* [ ] Specific micro-issues addressed in pull request 
* [ ] Specific "checkbox" areas addressed in pull request for each activity and lab Epic that was worked on 
  * from General Development Review Checklist
* [ ] Pull Request properly named
  * [ ] If manager: \[Module Name\] Week of \*/\*\*: \*Manager Name\*
  * [ ] If developer: \[Activity/Lab Code\] \[Activity/Lab Name\] Week of \*/\*\*: \*Reviewer Name\*
* [ ] Proper Stage Label per the General Development Review Checklist
* [ ] Proper Project Label

This checklist should be pasted into each review, and checked off completely by Sunday.

## General Development Review Checklist

The following checklist must be fully completed before an Epic deadline, and also serve as a general guide to development.

This checklist should be maintained and updated

#### The General Checklist for Devs

Developers should be developing curriculum with all of those requirements in mind. Each issue they are assigned should address items on this checklist directly.

Additionally, each pull request should have stage labels corresponding to the four stages. Please apply as many labels as applicable, for every item addressed in a stage, there should be that corresponding stage label applied.

#### The General Checklist for Reviewers

With regards to this checklist, reviewers should do the following:

* Paste this checklist into their Epic's description, and continually update it every week
* Provide _comments_ on developers' pull requests that **directly reference items on the checklist**
* In pull requests to `master`, reference stages or items that are completed
* Ensure that stage labels are being properly marked
* When entire checklist is checked off for an Epic, then that Epic should be completed and linked within a pull request to `master` to indicate completion

### General Checklist

#### General Items \(Apply to All Stages\)

* [ ] High-schooler friendly writing style, easy to understand
* [ ] Correct numbering
* [ ] Every card has code\* 
* [ ] 1 scroll per card\*\*
* [ ] Proper grammar, punctuation, capitalization, etc.
* [ ] Acceptable Styling per the Pull Request Checklist

\*Exception being hard and medium cards in labs as well as activity cards that just introduce concepts

\*\* If you have to scroll more than once to view the whole card, the card is too long

#### Stage 1 - Starting Content

* [ ] Content of cards is more accessible to beginners
* [ ] Micro to Macro Principle
* [ ] Titles for Concepts associated with each Card

#### Stage 1 - Lab Addendum

* [ ] Hard cards provide enough guidance for the student to finish task
* [ ] Mediums bridge Hards and Easys
* [ ] Easy cards provide solution, are line-separated
* [ ] Solution and starter code in Airtable and GitHub
  * [ ] Code is testable, not too general

#### Stage 2 - Finishing Content

* [ ] Logical card progression 
* [ ] Ample pictures/custom visuals \(copyright-free, Pexels is a great source\) 
  * [ ] Images placed _locally_ with &lt;img&gt; NOT Markdown 
* [ ] \(For activities\) Fleshed-out, real-life scenarios
* [ ] 2-3 Checkpoints \(Types: Short Answer, Image, Multiple Choice, Video, Autograder/Code\)
* [ ] All concepts fleshed out

#### Stage 2 - Lab Addendum

* [ ] Medium and easy cards split into hints 
* [ ] 2-3 code checkpoints, depending on length of lab
  * [ ] Solution Code for checkpoints

#### Stage 3 - Finishing Touches

* [ ] Correct formatting according to READMEs
  * [ ] Modules
  * [ ] Activities
  * [ ] Labs
  * [ ] Hints \(Medium + Easy Cards\)
  * [ ] Concepts
  * [ ] Checkpoints
  * [ ] With test cases for checkpoints if applicable
* [ ] Concepts for each card completely finalized, with correct README formatting

**Stage 3 - Lab Addendum**

* [ ] 5-10 test cases, correctly formatted according to READMEs

#### Stage 4 - For Reviewers Only

* [ ] Assigned modules' folders properly structured within topics
* [ ] Gem Amounts 
  * Labs: calculated using John's Code 
  * Activities: Predetermined amounts
* [ ] Have curriculum proofread by writing team \(currently Victoria Xu @vkxu657\)

### Stage 3 Breakdown

> Note: All elements of a unit \(Module,Activity,Topic,etc.\) are REQUIRED unless stated otherwise. Additionally, ALL concepts should be fully done by this point.

#### Topic README Format

**Github ID**

Each topic needs a `github_id` so that the server knows it is unique. There is a maintained Airtable for these ids. Developers should check in with their managers if the id is missing, and then with Kevin. The word `github_id` should be in a markdown `h1` tag like below:

```text
# github_id
1
```

**Name**

Each Topic needs a `name` field. The word `name` should be in markdown `h1` tag like below:

```text
# name
Postman Topic
```

**Description**

Each Topic has a `description` field to describe what the topic will help accomplish. The word `description` should be in markdown h1 tag like below:

```text
# description
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum
```

**Image**

Each Topic has an `image` field. The word `image` should be in markdown `h1` tag while the image `url` must be in an `img` tag:

```text
# image
<img src="images/dee.jpg">
```

**Image Folder**

Each Topic needs to point to an image folder where image\(s\) are being used. The word `image_folder` should be in a markdown `h1` tag like below:

```text
# image_folder
/Topic_Postman/
```

**Modules**

Each Topic has modules. To add modules to a topic, add the module's `github_ids` in a list. Add the word `modules` in a markdown `h1` tag and then add the `github_id`s in a list with \*'s:

```text
# modules
* 5
```

**Topic README Example**

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
/Topic_Postman/

# modules
* 5
```

#### Module README Format

**Github ID**

Each module needs a `github_id` so that the server knows it is unique. The word `github_id` should be in a markdown `h1` tag like below:

```text
# github_id
1
```

**Name**

Each Module needs a `name` field. The word `name` should be in markdown `h1` tag like below:

```text
# name
Some Module 2
```

**Description**

Each Module needs a `description` field to describe what the module will help accomplish. The word `description` should be in markdown `h1` tag like below:

```text
# description
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum
```

**Gems Needed**

Each Module needs a `gems_needed` field which is the number of gems needed to unlock the module. The word `gems_needed` should be in markdown `h1` tag like below:

**Note: Set it as 0 for now**

```text
# gems_needed
0
```

**Image**

Each Module needs an image field that visually represents the theme of the module.. The word `image` should be in markdown `h1` tag while the image `url` should be put in an `img` tag:

```text
# image
<img src="images/dee.jpg">
```

**Image Folder**

Each Module needs to point to an image folder where the image is being used. The word `image_folder` should be in a markdown `h1` tag like below:

```text
# image_folder
Topic_1/Module2_test/
```

**Final Example**

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

#### Activity/Lab README Format

**Github ID**

Each Activity/Lab needs a `github_id` so that the server knows it is unique. The word `github_id` should be in a markdown `h1` tag like below:

```text
# github_id
1
```

**Name**

Each Activity/Lab needs a `name` field. The word `name` should be in markdown `h1` tag like below:

```text
# name
Some Activity
```

**Description**

Each Module needs a `description` field to describe what the module will help accomplish. The word `description` should be in markdown `h1` tag like below:

```text
# description
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip.
```

**Summary**

Each Activity/Lab has a `summary` field to describe what the activity will help accomplish **in more detail**. The word `summary` should be in markdown `h1` tag like below:

```text
# summary
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum
```

**Difficulty**

Each Activity/Lab needs a `difficulty` field to indicate how hard the Activity/Lab is for the user. Add the word `difficulty` in a markdown `h1` tag, and put the difficulty under it:

There are 3 types of `difficulty`:

* Hard
* Medium
* Easy

```text
# difficulty
Hard
```

**Image**

Each Activity/Lab needs an `image` field that visually represents the theme of the module.. The word `image` should be in markdown `h1` tag while the image `url` should be put in an `img` tag:

```text
# image
<img src="images/bandanna.jpg">
```

**Image Folder**

Each Activity/Lab needs to point to an image folder where the image is being used. The word `image_folder` should be in a markdown `h1` tag like below:

```text
# image_folder
Topic1/Module2_test/Activity_4/
```

**Cards**

The `cards` fields is used to indicate: the name of the card, the order in which the card will be shown, as well as the number of gems that the card is worth.

* **Cards**

To define cards in an Activity, you have to have the word `cards` in a markdown `h1` tag. This is used to tell the server where the cards are:

```text
# cards
```

* **Card Key** 

Each card you define in the Activity README must have a corresponding filename as its key. For example if a card/hint was named 1.md then its key would be 1. The card key must be placed in a markdown `h2` tag like below:

```text
## 1
```

* **Card Name** 

Each card has a `name` field. Each name should be in a markdown `h3` tag like below:

```text
### name
Card 1 Github
```

* **Card Order**

Each card has an order field. The order is the last digit of the card key. If a card had a key of 1-2, then the order for that card would be 2. Each `order` should be in a markdown h3 tag like below:

```text
### order
2
```

* **Card Gems**

Each card has a `gems` field. The gems fields is used to indicate the number of gems earned when opening a card. If this for a medium/easy card, this field is for the amount of gems a student would **lose** for using the medium/easy card. Each name should be in a markdown `h3` tag like below:

```text
### gems
300
```

* **Card Concepts \(Only applies to Hard Cards\)**

To give a card concepts, write the word `concepts` in a markdown `h3` tag and list out the name of the concepts using an \* like below:

```text
### concepts
* concept_1.md
* concept_2.md
```

> Note: When defining the cards, please put them in order of difficulty. Hard cards should be defined first, Medium cards next, and last easy cards. Below is an example:

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

**Final Example**

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

#### Hint README Format \(Medium/Easy Cards\)

**Image Folder**

Each Hint needs to point to an image folder. 

```text
# image_folder
Topic1/Module2_test/Activity_7/cards
```

**Start of the Steps**

You must include the word `steps` in a markdown `h1` tag so the server knows when the actual steps of the hints start like below:

```text
# steps
```

**Step Key**

Next you **must** include the step key so the server can keep track of the individual steps. The Step key should be the hint/card name along with the step number in a markdown `h1` tag like this:

```text
## 1-2-1 Step 1
```

**Step Name** 

Under the hint name, you have to give the step a name with a markdown `h2` tag. **Please put the contents of name in a code block.** It should look something like this:

```text
### name
How to install VSCode
```

**MD Content \(You need to include this for each step\)**

To include the actual content for the step, include the `md_content` with a markdown `h2` tag. **Please put the contents of md\_content in a code block.** It should look something like this:

```text
### md_content
Hello world in js. This is how you do it
```

**Optional Fields**

* **Code Snippet**

To include a code snippet for the step, include the `code_snippet` with a markdown `h2` tag. **Please put the contents of the code in a code block.** It should look something like this:

```text
### code_snippet
def pls_work(): return True... maybe
```

* **Image**

To include an image for a step, you need to put a `h2` markdown tag and assign it to `image`

```text
### image
<img src="images/bandanna.jpg">
```

**Final Example:**

Note: You can always add more steps as long as you follow the above syntax.

```text
# image_folder
Topic1/Module2_test/Activity_7/cards

# steps

## 1-2-1 Step 1

### name
How to install VSCode

### md_content
Hello world in js. This is how you do it

### code_snippet
def pls_work(): return True... maybe

### image
<img src="images/bandanna.jpg">
```

#### Concept README Format

**Concept Name**

Each concept needs a `name`. 

```text
# concept_name
Concept name
```

**Image Folder**

Each Concept needs to point to an image folder.

```text
# image_folder
Topic1/Module2_test/concepts/
```

**Step Key** 

Next you **must** include the step key.

```text
# concept_name Step 1
```

**Step Name**

Under the hint name, you have to give the step a name with a markdown `h2` tag.

```text
## name
How to install VSCode
```

**MD Content**

Include `md_content` as below:

```text
## md_content
Hello world in js. This is how you do it.
```

**Optional Fields**

* **Code Snippet**

Include `code_snippet` like below:

```text
## code_snippet
def pls_work(): return True... maybe
```

* **Image**

Include an `image` like below:

```text
## image
<img src="dee.jpg">
```

* **Final Example:**

Note: You can always add more steps as long as you follow the above syntax.

```text
# concept_name
Concept name

# image_folder
Topic1/Module2_test/concepts/

# 1-2-1 Step 1

## name
How to install VSCode

## md_content
Hello world in js. This is how you do it

## code_snippet
def pls_work(): return True... maybe

## image
<img src="dee.jpg">
```

#### Checkpoint README Format

**Filename**

For the file name, name it the card that you want it to be associated with. So if you wanted to create a checkpoint for `1.md`, you would name the checkpoint file `1-checkpoint.md`.This checkpoint should be created AFTER the associated card.

**Name**

Every checkpoint needs a `name`:

```text
# name
Code Check in
```

**Cards Folder**

Every checkpoint needs a `cards_folder`:

```text
# cards_folder
Topic1/Module7/Activity_13/cards/
```

**Checkpoint Type**

This is to define the type of checkpoint. Put `checkpoint_type` in a markdown `h1` tag.

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

**Instruction**

This is what you would tell the user to do for a checkpoint. Put the word `instruction` in a markdown `h1` tag. Put the instruction content under the `h1` tag like so:

```text
# instruction
Submit a photo your Minsweeper code working
```

**Other Fields**

* **Criteria \(Required for Video and Image Checkpoints Only\)**

Criteria correspond to a rubric for TAs to grade a student's Image or Video Checkpoint.

You must declare where the criteria for a checkpoint would begin. You would do this by putting the word `criteria` in a markdown `h1` tag like so:

```text
# criteria
```

After that you can list each criteria in a markdown `h2` tag with a number at the end like so:

```text
## criteria_1
Does the student's board look like this:
```

* **Multiple Choice \(Only for MC Checkpoints\)**

You must declare where the choices for the checkpoint would begin. You would do this by putting the words `mc_choices` in a markdown `h1` tag like so:

```text
# mc_choices
```

Next you would define each choice in a markdown `h2` tag with a number at the end like so:

```text
## choice_1
```

* **Files to send \(Autograder Checkpoint Only\)**

These are the files that the student will submit if the student chooses to submit through their code to the `cli`.

```text
# files_to_send
main.py class1.py class2.py
```

**Test file location \(Autograder Checkpoint Only\)**

This field is used to tell where the test case folder is for the checkpoint.

```text
# test_file_location
Topic1/Module7/Activity_13/Tests/test_1
```

#### Checkpoint Examples

**Video/Image**

```text
# name
Code Check in

# cards_folder
Topic1/Module7/Activity_13/Cards/

# checkpoint_type
Video

# instruction
Submit a video to show your Minesweeper code is working

# criteria

## criteria_1
Does the student's board look like this?

## criteria_2
Does the student's code print the board out?
```

Here, the checkpoint would require the student to send in a video recording of their output to ensure that their code matches the listed criteria.

**Short Answer**

```text
# name
Print Statements Short Answer

# cards_folder
Topic1/Module7/Activity_13/Cards/

# checkpoint_type
Short Answer

# instruction
Submit a photo your Minesweeper code working
```

With short answer checkpoints, a student would send in a paragraph response to a provided prompt. This would naturally be suited for conceptual or theoretical questions which don't ask for code.

**Multiple Choice**

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

This is fairly self-explanatory. With MC checkpoints, a student would be prompted to answer a quick conceptual question using multiple choice. These checkpoints are suited for questions that have very short answers and so Short Answer checkpoints wouldn't be appropriate.

**Autograder**

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

With Autograder checkpoints, a student will send in their code to be tested by an autograder program that will compare the expected output with that of theirs. This is where test cases come into play.

#### Test Cases README Format

> Note: All test case files must have .test as their extension.

**File formatting**

 If there are multiple test cases, they need to be numbered in the order that they will be used.

**Your test case must be named after the associated lab/activity followed by a number:**

* minesweeper1.test
* minesweeper2.test
* minesweeper3.test

If you have input files, then make sure that their name has a .txt extension. **They should be in numerical order like so**:

* input1.txt
* input2.txt
* input3.txt

**Name**

Each test case must have a `name`:

```text
Board Function
```

**Inputs**

To write test cases, you must type "&gt;&gt;&gt;" followed by the name of the function that you wish to test. This is done so that the test case looks like the output on a command shell when you run the code. Since you will mostly be testing the main function it would look like the following:

```text
>>> main()
```

**Outputs**

Right after the declaring the function that you want to test, you would place that function's output right below it like so:

```text
>>> main()
Hello World!
```

**Handling User Input**

If your program needs user input, then you must include the following Python file:

[https://gist.github.com/wongband/597c126217a306ca4770931680417faa](https://gist.github.com/wongband/597c126217a306ca4770931680417faa)

The input.txt files should also have numbers. Specifically, they should have the same number as he testcase associated with them. For example, if you have input1.txt then that corresponds to minesweeper1.test.

If, for instance, the minesweeper1.test file needs to have the input of 42, all we have to do is to create an input1.txt with 42 in it. **Do not put a new line if your program does not output a newline.**

```text
42
```

**Minesweeper Example**

Below is the minesweeper1.test file. In this case we test the main function while passing a number 2 as its input. Below that function, the output is a printed board and a prompt for the user input.

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

> Note: Each test case file should contain 5-10 unique test cases.

