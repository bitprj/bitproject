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
* [ ] Adjust timeline in Zenhub Calendar
* [ ] Weekly Team Sync
* [ ] 1:1s with devs

### Weekly Manager Tasks

### Deadlines:

Friday: Friday deadlines are the fist draft deadlines for your team. This means that your team members should have finished their issues and submitted a pull request to your branch for review. You should take the next few days to work on any problems that come up after review. 

Sunday: Sunday deadlines are the final draft deadlines for you team. This means that you should submit a pull request to master with your team's completed work for the week. There will also be a form that documents your team's work for the week that is due. 

Tuesday: Tuesday deadlines are for the issues that need to assigned to your team. 

### Issues:

Issues are unresolved problems that developers need to address. As a manager, it is your job to raise issues for your developers and assign them each week. You should make sure that there are enough issues each week to be worked on, raising issues as you review your developer's work as well as in line for your long-term goals.

There are also other issues that should be raised and given as first-timer issues. These issues are generally less complicated resource wise compared to other issues. This does not mean that they are less difficult content wise.

All issues addressed should fully address the long-term plans set up!

### Milestones:

Milestones are used to organize your weekly team's weekly tasks. Issues are placed into your milestones to keep track of your team's work for the week. To create a milestone go to the issues tab in GitHub and there should be a milestones button to the left of the new issue button. Here you can create new milestones as assign tasks to your milestones. In addition your milestones should follow the naming convention of your team-week of- Tuesday of week. 

### Adjustments:

After all your weekly tasks are completed, assess your long-term plan and make any changes necessary. If a part of your activity is completed, assign the appropriate epic points. If there was not as much progress as originally thought, modify the long-term deadlines. Adjust overall long-term plan according to the week's progress and any feedback from developers. 

### Github Projects:

Github Projects are another source of organization for your long-term plans. You can use them to group issues of your long-term plan for a module and track the progress of completion. 

## Pull Request Checklist

Every week, there are a couple essential things that every manager should take care in pull requests. This checklist applies to both pull requests from developers' branches to managers' branches and from managers' branches to `master`. 

* [ ] **Branch updated from `master`**
  * [ ] Resolving all Merge Conflicts
* [ ] Spelling and grammar errors fixed
* [ ] Markdown Formatting
* [ ] Correctly spaced code snippets
* [ ] Code style followed
* [ ] Local images with &lt;img&gt; NOT Markdown 
* [ ] Splitting Up Cards \(no more than one scroll a card\)
* [ ] Readability Test: Automated Readability Index result of 9th grade or under \([https://readabilityformulas.com/free-readability-formula-tests.php](https://readabilityformulas.com/free-readability-formula-tests.php)\)
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

#### Checklist for Devs

Developers should be developing curriculum with all of those requirements in mind. Each issue they are assigned should address items on this checklist directly.

Additionally, each pull request should have stage labels corresponding to the four stages. Please apply as many labels as applicable, for every item addressed in a stage, there should be that corresponding stage label applied.

#### Checklist for Reviewers

With regards to this checklist, reviewers should do the following:

* Paste this checklist into their Epic's description, and continually update it every week
* Provide _comments_ on developers' pull requests that **directly reference items on the checklist**
* In pull requests to `master`, reference stages or items that are completed
* Ensure that stage labels are being properly marked
* When entire checklist is checked off for an Epic, then that Epic should be completed and linked within a pull request to `master` to indicate completion

#### Stage 1 - Starting Content

* [ ] High-schooler friendly writing style, easy to understand
* [ ] Correct numbering
* [ ] Every card has code\* 
* [ ] 1 scroll per card\*\*
* [ ] Content of cards make sense
* [ ] Proper grammar, punctuation, capitalization, etc.
* [ ] Micro to Macro Principle
* [ ] Titles for Concepts associated with each Card
* [ ] Acceptable Styling per the Manager Checklist

\*Exception being hard and medium cards in labs as well as activity cards that just introduce concepts

\*\* If you have to scroll more than once to view the whole card, the card is too long

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
* [ ] Acceptable Styling per the Manager Checklist

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
  * [ ] With test cases if applicable
* [ ] Concepts for each card completely finalized, with correct README formatting
* [ ] Acceptable Styling per the Manager Checklist

#### Stage 3 - Lab Addendum

* [ ] 5-10 test cases, correctly formatted according to READMEs
* [ ] Badge Gem Amounts correctly calculated using John’s code \(no diagram for activities\)

#### Stage 4 - For Reviewers Only

* [ ] Assigned modules' folders properly structured within topics
* [ ] Gem Amounts 
  * Labs: calculated using John's Code 
  * Activities: Predetermined amounts
* [ ] Have curriculum proofread by writing team \(currently Victoria Xu @vkxu657\)

