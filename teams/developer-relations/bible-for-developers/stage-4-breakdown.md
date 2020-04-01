# Stage 4 Breakdown

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

