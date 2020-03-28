# Curriculum Folder Structure

## Topics

#### Naming Convention

The name of the topic folder must include the word "Topic" in it. This so that the parser knows that this folder is a Topic.

**ex:** _Data-Structure-and-Algorithm-Topic_

Each folder in the root of the Github repo is going to be a Topic folder which has the following sub folders/files:

* [README.md](http://readme.md) - describes the the Topic
* images - a folder used to keep track of the images used for the [README.md](http://readme.md)
* module folders - module folders that belong to a Topic
* concepts - a concepts folder to hold all the concepts used in a topic

**Note: Name the images folder "images" and the concepts folder "concepts"**

#### Example of Topic folder structure

```text
- Data-Structure-and-Algorithm-Topic
 - README.md
 - images
 - concepts
 - Module1-Intro-to-Data-Structures
 - Module2-Intermediate-Data-Structures
```

### Modules

#### Naming convention

The name of the module folder must include the word "Module" in it. This so that the parser knows that this folder is a Module.

**ex:** _Module1-Intro-to-Data-Structures_

Each module folder would be inside of a topic folder. Module folders can be placed in many topic folders. Each module folder will have the following sub folders/files:

* [README.md](http://readme.md) - describes the Module
* images - a folder used to keep track the images used in the module README.md
* Activities and Labs folders - Activity and lab folders that belong to a module

**Note: Name the images folder "images"**

#### Example of a Module folder structure

```text
- Module1-Intro-to-Data-Structures
 - README.md
 - images
 - Activity1-TimeAndSpaceComplexity
 - Activity2-HashTables
 - Activity3-Queues
 - Activity4-Stacks
```

### Activities and Labs

#### Naming conventions

The name of each Activity must contain the word "Activity" in it and the name of each Lab must contain the word "Lab" in it.

**ex:** _Activity1-TimeAndSpaceComplexity, Lab5-nColorable_

Each Activity/Lab would be inside of a module folder and would have the following sub folders/files:

* [README.md](http://readme.md) - describe the Activity/Lab
* images - folder to keep track of the images used in the [README.md](http://README.md)
* cards folder - keep track of the cards associated with the Activity/Lab
* checkpoints - folder to keep track of the checkpoints in the Activity/Lab
* tests - folder to keep track of the test cases used in the checkpoints for the Activity/Lab
* student-starter - folder to keep track of the student's starter code

**Note: Name the cards folder "cards", images folder "images", checkpoints folder "checkpoints", student-starter folder as "student-starter" and the tests folder "tests"**

#### Example of Activity/Lab folder structure

```text
- Activity1-TimeAndSpaceComplexity
 - README.md
 - cards
  - 1.md
    - 2.md
 - images
  - image.png
 - checkpoints
  - 1-checkpoint.md
 - student-starter
    - main.py
 - tests
  - test1
```

