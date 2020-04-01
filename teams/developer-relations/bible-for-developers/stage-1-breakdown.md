# Stage 1 Breakdown

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

