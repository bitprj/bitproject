# Curriculum Folder Structure

## Topics

#### Naming Convention

In the root of the GitHub repo, make a folder with the name of a Topic. 

**ex:** Javascript

Each folder in the root of the Github repo is going to be a Topic folder which has the following sub folders/files:

* [README.md](http://readme.md) - describes the the Topic
* modules - a folder that contains Module readmes
* activities - a folder that contains folders of activities
* projects - a folder that contains folders of projects
* images - a folder used to keep track of the images used for the [README.md](http://readme.md)
* concepts - a concepts folder to hold all the concepts used in a topic

**Note: Name the images folder "images" and the concepts folder "concepts"**

#### Example of Topic folder structure

```text
- Data-Structure-and-Algorithm-Topic
 - README.md
 - modules
 - activities
 - projects
 - images
 - concepts
```

### Modules

#### Naming convention

Each module would be represented as a markdown file.

**ex:** OOP.md

Each module folder would be inside of a topic folder. Module folders can be placed in many topic folders. Each module folder will have the following sub folders/files:

* markdown files - markdown files to create/update modules
* images - a folder used to keep track the images used in the module markdown files

**Note: Name the images folder "images"**

#### Example of a Module folder structure

```text
- Modules
 - images
 - OOP.md
 - ES6-Syntax.md
```

### Activities and Labs

#### Naming conventions

The name of each Activity must be placed in an Activities folder and each Project must be placed in a folder called Projects

**ex:** Minesweeper, Time Complexity

Each Activity/Project would have the following folders:

* [README.md](http://readme.md) - describe the Activity/Project
* images - folder to keep track of the images used in the [README.md](http://README.md)
* cards folder - keep track of the cards associated with the Activity/Lab
* checkpoints - folder to keep track of the checkpoints in the Activity/Lab
* tests - folder to keep track of the test cases used in the checkpoints for the Activity/Lab
* student-starter - folder to keep track of the student's starter code

**Note: Name the cards folder "cards", images folder "images", checkpoints folder "checkpoints", student-starter folder as "student-starter" and the tests folder "tests"**

#### Example of Activity/Lab folder structure

```text
- TimeAndSpaceComplexity
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

