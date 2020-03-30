# Guide to Being a Reviewer

Reviewers are in charge of **curriculum departments.** Each department is a team of 4-6 people who work on different modules of curriculum. They will be tasked with a project, usually covering a topic, and a deadline. By this deadline, all activities, labs and workshops for that project should be completed.

## Starting Off: Receiving Module Assignments

All reviewers will be assigned an issue in the **bitproject** repository, to be completed within _3 days of assignment._

### Pre-approval Checklist

* [ ] Confirm modules to be done
* [ ] Finalize activities, labs and workshop list
* [ ] Confirm overall project deadline

### Post-approval Checklist

* [ ] Making Epics in a Project
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

## Weekly Checklist

* [ ] Review developers' work and provide a review according to the Manager Checklist 
* [ ] Ensure "first draft" pull requests are in **by Friday**
* [ ] Pull request to `master` should be in by **Sunday**
* [ ] Generate issues for the project based on feedback received and progress made the week prior
  * [ ] Ensure issues are made and set-up for next week's tasks 
  * [ ] Designate two issues _not being solved_ to be "first timer only" issues
  * [ ] Milestone should be set-up
* [ ] Adjust long-term plan and epic points for each module epic based on feedback and progress
* [ ] Adjust timeline in Zenhub Calendar

## Manager Checklist

Every week, there are a couple things that every manager should take care of for each dev's pull request:

* [ ] Spelling and grammar errors fixed
* [ ] Markdown Formatting
* [ ] Correctly spaced code snippets
* [ ] Code style followed
* [ ] Local images with &lt;img&gt; NOT Markdown 
* [ ] Splitting Up Cards \(no more than one scroll a card\)
* [ ] Readability Test: Automated Readability Index result of 9th grade or under \([https://readabilityformulas.com/free-readability-formula-tests.php](https://readabilityformulas.com/free-readability-formula-tests.php)\)
* [ ] Visuals make sense
  * [ ] Alternate text for visuals

This checklist should be pasted into each review, and checked off completely by Sunday.

## General Review Checklist \[TO BE DONE SOON\]

Stage 1: Content

* High-schooler friendly writing style, easy to understand
* Every card has code
* Minimal scrolling \(cards are not too long\)
  * bite-size
* Content of cards make sense
* Micro to Macro
* Logical card progression 
* Ample pictures \(copyright-free, Pexels is a great source\) \(no local URLs\)
* Proper grammar, punctuation, capitalization, etc.
* Correct numbering
* Titles in HTML comments
* \(For activities\) Real-life scenarios
* Checkpoints

Stage 1 - Lab Addendum

* Hard cards provide enough guidance for the student to finish task
* Mediums bridge Hards and Easys
* Easy cards provide solution, are line-separated
* Solution and starter code in Airtable and GitHub
* Medium and easy split into hints
* Code is testable, not too general

Stage 2: Finishing Touches

* Badge Gem Amounts in each card
* Concepts in each card - Airtable AND in cards as &lt;!--concepts={...}--&gt;
* Three criteria points
* Summary & Long Summary

Stage 2 - Lab Addendum

* 5-10 test cases 
* Badge Gem Amounts correctly calculated using John’s code \(no diagram for activities\)

Stage 3 - Uploading

* Make sure your work looks good!
  * I will upload to our website: bit-lab.herokuapp.com

