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

### Pre-approval: What To Do

* [ ] For each module,create a document that outlines the planned curriculum\(make sure to format it properly and according to the example\)
  * [ ] Make sure learning objectives are written and formatted properly
  * [ ] Make sure activity titles and descriptions written and formatted properly
  * [ ] Make sure lab titles and descriptions written and formatted properly

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

### General Checklist \(Applies to All Stages\)

Before going into a stage-by-stage breakdown, here's a general overview of things to keep in mind.

#### Writing Style

First and foremost, we want all our developers to use a conversational writing style when making cards. This is because the target audience for our curriculum is high school students, and our goal is to make technical education as accessible as possible. Writing as if you're having a conversation will keep students more engaged. When in doubt, think **blog post** instead of **calculus textbook**.

#### Numbering

It's crucial that each card is numbered correctly so developers can keep lessons organized and students can follow a logical progression. BitProject uses two numbering schemes, one for Activities and one for Labs.

Here's an example of an Activity \(pretty self-explanatory\):

![Numbering for Activity Cards](../../../.gitbook/assets/screen-shot-2020-03-29-at-3.00.05-pm.png)

And here's an example of a Lab:

![Numbering for Lab Cards](../../../.gitbook/assets/screen-shot-2020-03-29-at-3.06.54-pm.png)

Each hard card is labelled as a single number.  
Going off of the above example, **1.md is the first hard card**, and **2.md is the second hard card**.

To label medium cards, simply add another number associated with its order.  
In the above example, **1-1.md is the first medium card associated with the first hard card**, and  
**2-1.md is the first medium card associated with the second hard card**.

To label easy cards, add another number associated with its order \(3 numbers total\).  
In the above example, **1-1-1.md is the first easy card associated with the first medium card associated with the first hard card.** Can you translate 2-1-1.md into plain English?

#### Card Length

Cards should be concise. Ideally, you should not have to scroll more than once to view the whole card. Stuffing a ton of information in a single card can be too overwhelming, so try to keep things brief and split up topics as much as possible.

#### Writing Conventions

Last but certainly not least, proper writing conventions such as grammar, punctuation, capitalization, etc. should be utilized.

### Stages

Here's an in-depth breakdown of how cards progress in the BitProject system.

#### Stage 1 - Starting Content

**Card content should be accessible to beginners**, meaning someone with no prior knowledge should be able to follow the content. This goes hand-in-hand with using a conversational writing style.

Next up is what we call the **Micro to Macro Principle**. For labs and activities, please start at a micro level and then move up. For example, students should not code the main\(\) function first. As a rule of thumb, you should never have to utter the words “this function will be coded in a later part”. Every hard card should work on its own and not have to rely on later work for it to work out.

![Micro &#x2014;&amp;gt; Macro!](../../../.gitbook/assets/smalltobig.jpeg)

**Images**! Make liberal use of images \(like the one above\) in your cards. It's much easier to visualize a concept than to read three paragraphs of text. Obviously, text is necessary, but pairing text with visuals is immensely helpful. Also, images help break up blocks of text, making it easier on the eyes. Please use copyright-free images, Pexels is a great source. Make sure images are embedded using &lt;img&gt; tags and not URLs.

Activities and Labs will feature coding tasks for students to complete. For these, developers should implement what we call **checkpoints**—Python console output that serves as a frame of reference for students to make sure their code is doing what it's supposed to be doing.

**Titles**. These should be included in HTML comments at the top of each card, not in the file name itself \(remember, cards are named numerically\). Along with titles, **concepts** covered in the card should also be contained in HTML comments. Here's an example:

![Titles an concepts love swimming in HTML comments.](../../../.gitbook/assets/screen-shot-2020-03-30-at-9.48.40-am.png)

**Card length** should be reasonable. Ideally, keep the entire card viewable with at most one scroll.  
Students will have a hard time staying focused if a card is too long, and shorter cards are easier to digest. Try to split up topics as much as possible.

This one is pretty self-explanatory, but make sure your cards progress in a way that makes sense.

#### Stage 1 - Lab Addendum

![Not a paid endorsement, this picture just fits perfectly.](../../../.gitbook/assets/inthelab.jpg)

When creating a Lab, you are essentially giving the student a problem to solve, breaking it down into steps, with each step subdivided into cards of hard, medium, and easy difficulty. An example might be to code a Python program that can solve Sudoku.

When it comes to Labs, there are a number of things to keep in mind.

**Hard cards** are, by definition, _hard._ A hard card for the Sudoku Solver Lab might explain the game of Sudoku and have a teeny-tiny bit of **starter code** at the end. Keep in mind that, although this card should stretch the student's brain, it should also provide just enough guidance for the student to finish the task. The main thing to keep in mind is you _should NOT_ leak any hints_._ Example [here](https://github.com/bitprj/curriculum/blob/master/Data-Structures-and-Algos-Topic/labs/Lab6_Sudoku_Solver/Cards/1.md).

**Medium cards** are probably the most difficult cards to make, since you have to find a delicate middle ground between hard and easy. That said, keep in mind that the goal of medium is to serve as a bridge between hard and easy. You start to squeeze out a few hint droplets into the student's cup, but don't fill the entire cup. Example [here](https://github.com/bitprj/curriculum/blob/master/Data-Structures-and-Algos-Topic/labs/Lab6_Sudoku_Solver/Cards/11.md).

**Easy cards** should literally walk the student through the problem step-by-step. Imagine leading a blindfolded person through a mine\(sweeper\) field. Functions should be completely written out, and explanations should be given for _everything._ Expanding on the juice analogy—fill the student's cup! Example [here](https://github.com/bitprj/curriculum/blob/master/Data-Structures-and-Algos-Topic/labs/Lab6_Sudoku_Solver/Cards/111.md).

It's probably a good idea to first make your hard and easy cards for a topic, then do medium last.  
That way, you give yourself boundaries that your medium card shouldn't cross.

A word about **code**. All Lab cards should contain code, with varying degrees depending on card difficulty. Make sure code is _testable_, meaning a student can copy-paste your code into an IDE and have it output something meaningtul to the problem at hand.

#### Stage 2 - Finishing Content

The bulk of your content has been finished. Here are a few more things to top off your cards.

Each card should reward the student a certain number of **gems** upon completion. Think of these as currency in a video game. Students will be able to spend gems to unlock things like hints as they progress further through curriculum tracks. Gem numbers should be included in the README file for the Activity/Lab.

![Beautiful. Just beautiful.](../../../.gitbook/assets/gems.jpeg)

For each Activity and Lab, **three criteria statements** must be provided. Each criteria should outline an important takeaway from the Activity/Lab. Teachers will be referencing this criteria when grading students’ videos of Activities and Labs, and students will have to meet all criteria to proceed. The criteria can be in statement or question format and should be included in the README file for the Activity/Lab. Here's an example:

![A bucket list of things to learn for the student.](../../../.gitbook/assets/screen-shot-2020-03-30-at-11.11.57-am.png)

Each Activity/Lab should contain a brief **summary** describing it using 1 sentence only. In addition, please provide a **long summary** that expands on the main concepts covered in the Activity/Lab, about 3-4 sentences total. Here's an example:

![Example of an Activity summary.](../../../.gitbook/assets/screen-shot-2020-03-30-at-1.40.58-pm.png)

#### Stage 2 - Lab Addendum

For each lab, **test cases** must be provided. Make sure your lab is concise enough so that test cases can be made. For example, if you were making a Wheel of Fortune lab, don’t ask users to make their own lists of possible messages. Instead, create the messages yourself and have them simply make a list out of those predefined messages. In the scenario where students get to create their own list, it would be impossible to actually define test cases for each student’s custom list.

For the test cases, simply provide a document detailing what should be inputted and its output. There should be around 8-10 test cases per Lab.

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

* [ ] **Bit Learning Management System \(LMS\)**

  We have a LMS built to help us teach students step by step how to tackle complex and technical problems. In addition, we are open source so we are looking forward to finishing up LMS and creating small enough issues to let anyone contribute to our project.

For the LMS to work, each module has a folder structure to follow.

Walk through example:

On the Bit curriculum Github, there is a module you should use as an example when trying to structure your module. Follow along by going to [https://bitproject.org/curriculum](https://bitproject.org/curriculum).

Once at the link it should look like this. We’re going to go into the Data-Structures-and-Algos-Topic.

![](https://lh6.googleusercontent.com/qvvB1JPKR_jm5GzbY8MyJtZ5XfJkzJiOsZTS6KswZLK_ivUf5REWuELLhDuImuoqxbSveiiCCtG8ok63KRArxcv28cCQC8ROfS2d2jkTB-9RlT7aCPOdmp95tXau3xAebj1o8VDy)

You see how each module’s names are formatted Module\# name. Please do only use dashes \(-\) between words as any colons, semicolons, and slashes \(: ; / \) will mess with Github and cause trouble.

Then into Module1-Intro-to-Data-Structures-and-Algos

![](https://lh5.googleusercontent.com/b2jiQTcHdt07reu4h8trpAbq57cAEV5UpZfxhrImoP_a-f5mhYcUwCupfMSdX46RcXmWSZoJeQG_Ld7yauBa1ULvIhHKxcZcD5zdfn5si2XZBpvRQwkNyMV7JEn8P2-ZCNDwzQ8e)

Again, you see how activite’s names are formatted with Activity\# name and it’s title in one chunk but capitalized every first letter of each word. Please do only use dashes \(-\) between words as any colons, semicolons, and slashes \(: ; / \) will mess with Github and cause trouble.

Then into Activity1\_TimeAndSpaceComplexity

![](https://lh4.googleusercontent.com/8ErpFq3ixxWpwUZmLatNBRFG9tJYGSds9zc5YIm-fmwe76aScJzgWD89f319MnhO-kAiNNBNM8DGMISQDXVsE63gduIpm8B5Gu1ddA5pCyLRpHAm3FmSwd1lne5VKEDnO9ecWmYM)

It should look something like this:

![](https://lh4.googleusercontent.com/Axm24Rp0aiNJ4PDkF9uyeIEJgFu08o2vam--oonqprZkYsvj-9DE4giGCxczXcd74hUvdtkKpyoQbwn05zOXRmK0DM4xBYsdEMY61mR9saD0Ex2mtOsWyVHacFiCgRtzjYEFEeWK)

You can already see the way that this activity is being organized. Cards, checkpoints, and images goes in their own folder. Check out each of the folders and see how things are named.

Cards are named from 1.md to \#.md.

Checkpoints are named card\#-checkpoint.md.

Images are named what the image is related to.

Notice, the most important here is the README.md. The format of readmes have been documented here [https://about.bitproject.org/teams/engineering/readme-formats](https://about.bitproject.org/teams/engineering/readme-formats). Please follow the documentation and use the example in Github as a guide. Make sure you have all the information.

\*NOTE: Gems will be explained in the next step so don’t worry about it yet.

* [ ] **Gems**

  Gems are something that students will receive upon completing a set of activities. Due to the difference in difficulty for each set of activities across all the modules, a set amount of gems does not make sense. To solve this issue, one of our members had created a Python script that you can run to calculate the number of gems that you should record in the readme of each activity.

The idea is that if you per-assign a certain number of gems to each hard card and you know the amount of mediums and easy's under that given hard card, you can use the algorithm to calculate the entirety of the gem amounts for the rest of the cards.

The script is written to assign points based on the types of cards. It’s in Python so make sure you have some sort of Python editor available for use. Download and open to follow along:  
Calculates the amount of exp to subtract from medium

**and easy cards for a single hard card \(NOT the entire lab\)**

def assignPoints\(basePts, numCards\):

```text
  # subtract the bonus
  bonusRate = 0.1
  bonus = bonusRate * basePts
  basePtsNoBonus = basePts - bonus

  # get amount to subtract for medium and easy cards
  totalWeights = numCards["medium"] + numCards["easy"] * 2
  subAmountM = basePtsNoBonus / totalWeights
  subAmountE = subAmountM * 2

  # floor amts
  subAmountM //= 1
  subAmountE //= 1
  print("Hard card: " + str(basePts))
  print("Medium card: " + str(subAmountM))
  print("Easy card: " + str(subAmountE))

  def main(): 
      numMed = int(input("Enter number of medium cards under this hard card: ")) 
      numEasy = int(input("Enter number of easy cards under this hard card: ")) 
      basePts = int(input("Enter the exp split amount for this hard card: "))

      numCards = {"medium" : numMed, "easy" : numEasy}
      assignPoints(basePts, numCards)

  n = 0 
  while (n >= 0): 
      main() 
      n -= 1
```

_Step 1:_ Open the file with a Python editor.

_Step 2:_ If you only need it once, just run the program. If you want to calculate more than once, you can change the number that the variable N \(line 30\) is assigned as. It’s set up to loop N times.

```text
                     ![](https://lh6.googleusercontent.com/MX-Beqd-BXYmCmBiTk6uFs-ZCIFyXAFP_xLaktc8kyKe3_VOtJnVHYnS8j7b917p8jns9ihDTFZJmhgXO4mQNZD0AGWtdri8dYQkxa_nRoAkMh8NvBTJdMJgFPwbfYNv3_-clbn0)
```

_Step 3:_ Enter all the inputs requested and press enter.

```text
                   ![](https://lh3.googleusercontent.com/akLNN7ownnjpvsJm1ZmDl-gpzdHHU7WIis6DJ8RYbG0oRrmdwrm-ea-jlzJXVJ84MU3CqlUK0BnZVBEBbTrnZMzMBytgfNKGrrwA8HLg2wDEnJgKWQRYGk4iby8MT7gA3lLdxkqO)
```

_Step 4:_ With the results, please consult Kevin for the number of gems.

* [ ] **Proofreading by the Writing Team**

  This is the very last step of development. Please send your contents to the writing team \(currently Victoria Xu @@vkxu657 on Github\).

This is important to make sure all the content is syntactically and grammatically correct so students won’t have trouble with the material for maximum understanding.

It is your responsibility as a manager to raise any issues that are reported and issued to a member of your team to fix it by a deadline. All the writer’s changes should be integrated into your weekly PRs.

