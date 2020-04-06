---
description: 'Organizing a workshop for your duos, week by week.'
---

# Managers' Responsibilities

This page is a guide for week-by-week responsibilities. Responsibilities for every week regardless of status will first be outlined, and then responsibilities for each week pertaining to the 3 or 5 week plan will be described.

**Each manager should persistently update every checklist, and ask their developers to update the checklists in the issues assigned to them.**

## General Weekly Responsibilities for Managers

_This checklist will be in an issue with the label `weekly-manager` and a title format: \[Topic Name\] \[Project Name\] Week \[x\] of \[y\]: General Manager Responsibilities._

* [ ] 1-1 Zoom meeting with duos
* [ ] "First draft" of work by Friday
  * [ ] Pull request from your devs' branch to your branch is submitted, _referencing all relevant issues_
  * [ ] Provide feedback via pull request review by **Saturday**
* [ ] "Final draft" of work by Sunday
  * [ ] Pull request from your branch to `master`, _referencing all relevant issues_
  * [ ] Pull request should link all appropriate issues
  * [ ] Set Kevin \(@kavuong\) as reviewer
  * [ ] Set up pull request to `master`
  * [ ] Provide feedback via pull request review by **Tuesday**
* [ ] Be available daily on Slack/GitHub to answer questions and follow-up with team members
* [ ] Generate **normal issues** for the week's Epics
  * [ ] With the label `specific-issue`
  * [ ] If applicable, generate issues for other weeks' Epics as well
  * [ ] Ensure each issue is linked up to the correct Epic
* [ ] Update GitHub Project of status of issues
  * [ ] GitHub project should be set up in the bitprj organization
* [ ] Completion of all dev and manager checklists for that week
* [ ] \(If not first week\) Convert all of your PR feedback into _normal issues_
* [ ] "[General Slide Checklist"](../#general-slide-checklist) fulfilled

**This checklist will be made by your head every week and assigned to managers. When setting up your "final draft" pull request, please link this issue.** Each of these issues will have the label `weekly-manager`.

**Also please note that for the rest of the checklists in this page, it is each manager's responsibility to create issues for each week for themselves and their developers, as well as keep the issues updated via accountability and GitHub Projects.**

As a baseline, each week every manager needs to schedule a 1-1 Zoom meeting with each of their assigned duos. This 1-1 allows the manager to outline responsibilities for the week and get on the same page as the devs. By the end of this 1-1, each dev should have a clear understanding of how they are going to tackle the tasks for the week. This plan should be **documented** in meeting notes, and pushed to [bitprj/meetings](https://github.com/bitprj/meetings).

By Friday, each duo needs to submit a pull request indicating their first significant attempt at the assigned work for this week. This should be strictly enforced. Feedback must be given by Saturday \(preferably early as possible\). As a manager, please encourage your developers to finish all tasks as soon as possible when the circumstances permit. That way you get more time to invest in quality assurance and a better workshop for your devs and Bit.

By Sunday, each manager needs to submit a pull request to `master`. All relevant issues should be closed in the PR's body, including weekly issues, weekly Epics \(and if applicable: project Epics\). Be sure to set your head as a reviewer.

Each week, **normal issues** should be assigned. The Epic issues cover what should be done on a week to week basis. However, **all** project-specific problems that come up in discussion or development should immediately be raised as an issue and a deadline, and linked to the proper weekly Epic. For example, interactive component ideas, specific issues pertaining to slides \(visuals, content, context, styling, etc\), lab conversion issues... any task you can think of regarding your duo and their workshop should be immediately raised as an issue and placed under the correct Epic. The normal issues should be raised **throughout the week** and should spawn from constant communication with your devs as well as your evaluation of what needs to be done to get the weekly goals completed.

All of your issues \(and Epics\) should be tracked in your personal GitHub projects. By enforcing the naming structure and labels \(see below "Starting Out"\), combining that with a GitHub Project to track statuses will help you a great deal with managing what still has to be done on a weekly basis.

Pull requests should be reviewed by your head and yourself. Please ensure that all feedback is made into issues for the next week.

The ["General Slide Checklist"](../#general-slide-checklist) should be completed by each duo each week. **Copy and paste this list into every pull request review,** and ensure that each box is checked honestly.

**This issue should be completed every week.**

## Starting Out \[Week 1 Set-Up\]

![Flowchart for Starting Out](../../../../.gitbook/assets/workshop-flowchart-page-2%20%281%29.jpeg)

### Devs' Checklist

_This checklist should have the label `weekly-dev`with a title format: \[Topic Name\] \[Project Name\] Week 1 of \[y\]: Dev Set-Up._

* [ ] Form duos
* [ ] Pick Topic
* [ ] Decide whether to choose existing idea \(3 weeks\) or pursue original idea \(5 weeks\)

**For first-timers to MDX-Deck:**

* [ ] Clone MDX-Deck [Repository](https://github.com/bitprj/mdx-deck) locally
* [ ] Navigate to local repo folder, run commands `npm install` and `npm start`
  * [ ] Check that your site is running at `localhost:8000`
* [ ] Create new .mdx file under `mdx-deck/decks` folder
  * [ ] Change this file
  * [ ] See changes in your .mdx file at `localhost:8000`

Please make sure that MDX-Deck is working on the devs' \(and your\) system to ensure that you can see their work and be able to diagnose problems fully.

### Managers' Checklist

_This checklist should be in an issue with the label `weekly-manager` and a title format: \[Topic Name\] \[Project Name\] Week 1 of \[y\]: Manager Set-Up._

#### Set-up

* [ ] If new devs: get them started with MDX-Deck per the MDX-Deck first-timer checklist above
* [ ] If new manager: create project to track all of your issues
* [ ] If new manager: clone MDX-Deck onto your machine per the checklist above
* [ ] Create epics for each duo's workshop on GitHub
* [ ] Generate an **Epic issue** on bitprj/mdx-deck for your workshop with the following format: \[Topic Name\] \[Workshop Name\]
  * [ ] Set label as `project`
  * [ ] Set up weekly **Epics**  as a checklist within this issue
  * [ ] Set devs as assignees
  * [ ] Include deadline in issue
* [ ] Generate **Epic** issues on `bitprj/mdx-deck` for every week with the following format: \[Topic Name\] \[Workshop Name\] Week \[x\] of \[y\]
  * [ ] Set label as `weekly`
  * [ ] Have appropriate checklist within issue
  * [ ] Include deadline in issue
  * [ ] Set devs as assignees
  * [ ] Link these epics with your project epic \(yes, epics can be linked to epics!\)

#### Checking Devs

* [ ] Ensure that they have completed the installation process
* [ ] Finalize Topic 
* [ ] Determine whether they will choose idea or create new idea

By following this checklist, you will have set up your work environment. You should always be completing all of your work in GitHub, and be updating the Epics and issues referenced above.

Your head will be periodically monitoring your project, Epics and issues.

## Next Steps

If your duo chooses an idea, they will follow a **3 week process.**

{% page-ref page="responsibilities-for-choosing-your-idea.md" %}

If your duo creates their own idea, they will follow a **5 week process.**

{% page-ref page="responsibilities-for-creating-your-idea.md" %}

## General Slide Checklist

Before starting the process, developers should be aware that these requirements must be met on slides **every week:**

* [ ] Precise headers
* [ ] Appropriate formatting 
* [ ] Correct spelling, grammar, and punctuation
* [ ] Concise text \(includes clear descriptions without tangents\)
* [ ] Smooth transitions \(includes references to previous slides, if needed\)
* [ ] Consistent pacing \(includes significant and meaningful content\)

Developers must ensure this is fully addressed every week.

Managers must copy this checklist into their pull request review and follow-up to make sure every check is completed.

