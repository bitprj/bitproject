# Guide to Being a Manager

**Italics indicate sections that still should be reviewed.** 

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

### Pre-approval: What To Do

* [ ] For each module,create a document that outlines the planned curriculum\(make sure to format it properly and according to the example\)
  * [ ] Make sure learning objectives are written and formatted properly
  * [ ] Make sure activity titles and descriptions written and formatted properly
  * [ ] Make sure lab titles and descriptions written and formatted properly

## _Module Assignments Documentation \[Ismail\]_

### Role of Epics + Assigning Epic Points

Epics represent long-term \(in the form of GitHub issues\) that will keep you on track to finish weekly assignment,activities & labs, and entire modules. These epics should be assigned points not based on how long they will take to complete but the overall, implementation based difficulty. Activity,Lab ,and workshop epics are assigned different points and they add up to represent the total weight/points of an entire module.

### Explanation of Role of Issues \(curriculum issues\)

Issues are assigned weekly to developers and represent a week's work that will help you reach your epics. These issues should help you push yourself further down your Epics. They should be succinct enough\(and must also follow the given format on GitHub\) for developers to understand but not get overwhelmed by too many details or work.

### Explanation of Role of Milestones

Milestones represent a person's and a team's weekly goals. They are comprised of curriculum issues and represent how much progress a team or person has made during a week. They will help you keep track of everyone's weekly work quota and your own work.

### Adding Issues to Epics \(Modules + Activities + Labs\)

Issues\(GitHub\) should be added to Epics. On a higher level, they represent what things need to be down in order to take down an Epic and will help you breakdown your goals into more tangible ideas and tasks. Module,activities, and lab Epics will be given smaller issues that break them into more ,as previously stated, bit-sized chunks that you can further break down into weekly issues and Milestones.

### Long-term Plan

A long-term plan should be clear for not only yourself but outsiders who might view it as well. It should follow a set format\(as shown below\) and should outline both major points that need to worked on and the time frame on when these issues will be dealt with. It should be realistic and extra care should be taken into considering that deadlines that you set might need to be adjusted\(so give yourself some "wiggle room"\)

`Overview of things to do:`

* `Create section on Python Class and other OOP concepts`
* `...`
* `Recycle older tutorials into new sections for the current module`
* `Add more descriptive visuals to currently-made activities`

`Weekly Goals:`

`Week of April 23th: Start outlining foundation cards`

`Week of April 30th: Start recycling older cards for the new Python tutorial module`

`...`

### ZenHub Calender

You should use ZenHub as a visual deadline guide and reminder. You will create Epics that will represent blocks on ZenHub. You will then adjust their size according to their perceived start date and deadline. You will also create sub-epics\(i.e activity,workshop labs, etc.\) that will also have their own deadlines\(that will build up the main module epic\).


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
* [ ] Weekly Team Sync
* [ ] 1:1s with devs

## _Weekly Manager Checklist Documentation \[Owen\]_

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

## _Weekly Code Review Documentation \[Michelle\]_

Performing code reviews is an incredibly important step, and this function has to be done for every pull request for each of the developers every week. To start you dev should have requested a review from you. If not, please gently remind them or just request yourself. Then you should see a geen "leave a review" button and pressing that will lead you to a page displaying the code differences. You should leave comments on the code that you are viewing with specific things that they can improve on in their nect iteration.

These specific changes should all contribute one way or another to the "Pull Request Checklist" as shown above. This checklist has to be pasted into each pull request. When reviewing, it is important to focus on both the "macro" and the "micro" issues that need to be resolved. This check list helps reviewers raise issues and review in a more efficient manner.

Stemming from an effort to be more transparent and let developers be aware of how their work contributes to the organization as a whole, this list both ensures proper workflow and a more stylistically workflow. As more and more of the list is checked off, the developer is able to see their progress. Ideally, the list for a specific PR is completely checked off by the end of the week.

## _Quality Assurance Procedures for Managers and Developers \[Jason\]_

We want to the developers and the managers to provide give their input for each aspect of our projects. Therefore, we need procedures that allow the developers to quickly and effectively work together to complete tasks while maintaining a standard of quality.

### Procedure:

* [ ] Managers and Kevin conduct code reviews through GitHub
  * [ ] Checking Issues and contributions
    * Each time a developer makes a Pull Request, they need to provide a list of check boxes of items they addressed for their work that week.
    * When managers review each Pull Request, they must check to ensure that all assigned issues in the milestone were completed and the checkbox contributions match the assigned issues.
  * [ ] Every checkbox must be addressed with a comment by the reviewer
    * A comment can acknowledge that the developer did something correctly or give constructive feedback.

## _Revision by Head of Developer Relations and President \[Jeff\]_

Here at Bit, we place heavy emphasis that all content and material developed by Bit is up to our standards. In addition to material being reviewed by respective managers, the material will undergo further review by the head of Develop Relations, Kevin Vvuong, as well as the President of Bit Project, Daniel Kim. We have many developer teams at Bit and this process is necessary to ensure all material is synchronous and consistent.

Kevin will audit a random Pull request everyweek from a developer to a manager and ensure proper feedback is being provided. While Kevin is auditing, he will be looking to ensure the content matches Bit Project's long term goals and is consistent with the other material. 

Daneil, as president, will also audit Kevin's pull requests to ensure quality is consistent through all curriculum by Bit Project. It will conducted in a similiar process to Code Reviews performed by managers. 

In order for curriculum to have a level of quality expected of Bit Project, we have implemented 3 checks. 

 1. Approval by Manager

 2. Approval by Kevin Vvoung

 3. Approval by Daniel Kim

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

