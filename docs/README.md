# QA Workflow
## Quality Assurance (QA)
QA is a systematic and planned process implemented to provide confidence on the developed product and fulfill its quality demands for the customers. This cannot be mixed up with Quality Control, which objective is to determine which are the quality requirements for the QA to fulfill. And last, there is Testing, process that detects the errors in the product.

![](https://github.com/VoZeS/QA-Workflow/blob/main/docs/images/QA_QC_Testing.jpeg?raw=true)

## QA in Video Games
Quality Assurance in videogames is by far one of the most important process in _Video Game Development_. The QA Process is the one that prevents all videogames to be plenty of _bugs_ and _glitches_ breaking the game. So, for that, just like Programming needs programmers and Art needs artists, Quality Assurance needs also a team.

![](https://github.com/VoZeS/QA-Workflow/blob/main/docs/images/TeamBuildingDiagram.png?raw=true)

### QA Team
QA Team may be the most undervalued team in game development, yet the most important, so they are responsible of finding all errors that break the game experience. To do so, there are different charges and responsibilites inside their team:

* **QA Tester:** Testers need to know what are they doing. Seriously, they have to know what kind of videogame are they playing, what is its purpose, which are its requirements and how is supposed to be the videogame to know when something related to gameplay, prograssion, tech or graphics do not fit in the game like it should, so they can report it. But, how do they do that? By playing and replaying the videogame, chapter, level, or even screen over and over. It is not as fun as it sounds. Remember they do not have to play for fun, they have to play for finding the maximum errors as possible. Once they have found a issue, they have to create a proper documentation of the error to communicate it to programmers, artists or whoever that error concerns. Then, they have to test the fixed issues to ensure it has been fixed.

* **Senior QA:** These are just experienced game testers. For that, they are often responsible for testing bigger parts of the game or the most important ones. They might mentor Junior QA Testers.

* **QA Lead:** To become a QA Lead, you have to be an experienced tester. Leads manage their tester's team, organize work schedules and playtesting sessions and, usually, can be considered as mentors for their team members testers.

* **QA Director:** Having started as testers, directors do no test anymore. This role exist when the company is big enough to have multiple projects simultaneously or when providing outsourced QA Services. Their job is to manage and supervise all QA Teams existing at that moment. 

* **QA Automation Tester & QA Test Engineer:** These roles are more dependable in QA. The first one is responsible to automate the testing process to save maximum time as possible. He/She needs to have certain level of programming, so they might have to create a script for specific repeatable actions. The second role's job is to program improvements for needed tools and processes to test the game. These oversees the project from a production Point of View.

### Methodology: Agile Vs. Secure
There is not only one way to get the final product without errors. In fact, there are two recognized methods used by the companies, depending on what and how they really want to be their game.

* **Agile:** The first methodology is about circles. Yes, metaphorically talking, is a circular process. That is because it is an inflected method ready to make any change depending on their feedback.

Inside this methodology work, there are two more types of agile work:

-- **Scrum:** This type is based on performing periodic intervals of work, called _sprints_. Each sprint has a fixed duration and at the end a partial delivery is made with the progress. This methodology has 4 stages:

**Planning:** the objectives of the sprint and the steps to achieve them are based.

**Execution:** Involves the development of objectives and includes a brief daily meeting to review the work.

**Review:** the finished result or prototype is presented.

**Retrospective:** the way in which the project has been executed is analyzed, detecting possible failures and points of improvement for the next sprint.

-- **Kanban:** For this, a scheme made with notes or post its is used. This way you can see the status of the work at all times, including tasks to be done, in progress and completed. This methodology divides the project into small phases and the tasks that move the work forward are carried out continuously.

![](https://github.com/VoZeS/QA-Workflow/blob/main/docs/images/agile.png?raw=true)

* **Secure:** This method, is linear and sequential. For that, in the beginning of the process the team defines its purposes and goals to state a plan for its project. For that, there are originally 5 stages to do so:

-- **Requirements:** All the client's requirements are listed, in this way the next phases can be planned without too much client involvement, but maintaining fluid communication until the development is complete.

-- **Design:**  The design phase is divided into sub-phases of logical design and physical design. Logical design is when ideas are brainstormed and possible solutions theorized. The physical design sub-phase is when all those theoretical ideas and schemes are turned into concrete specifications.

-- **Implementation:** In this phase, the programmers or developers assimilate the requirements and specifications of the previous phases, and produce the code or base to make the project a reality.

-- **Verification:** The client reviews the product to ensure that it meets each requirement established at the beginning of the project. The purpose of testing is to verify the quality of the software or product. In this phase, possible defects can be seen.

-- **Maintenance:** During this phase, the customer will regularly use the product, and may discover more faults or possible inappropriate features. The team will then apply the solutions that are necessary for the client to be satisfied.

![](https://github.com/VoZeS/QA-Workflow/blob/main/docs/images/waterfall.png?raw=true)

### Bugs Report
#### Step 1: QA Testing
##### Internal QA Test
All errors that might be in your game should be detected in QA Testing sessions. This sessions will take place in order to test all new mechanics and code incorporations. So, if a bug is found, is needed to be reported. Internal QA Testing may also be known as Bug Testing. So, in this process, QA Testers (Juniors, Seniors and Leads) test the game to fins bugs and report them, just to assure the game is not broke and, if it is, fix it in time.

##### External QA Test - Playtesting
External QA Testing is also known as Playtesting. This process is quite different to the Bug Testing. On the one hand, companies do not get professional QA workers nor developers. The people responsible of playing the game may be just regular players. Avoid family members or friends, they are so close to you and they will be biased, and that is the most important thing about playtesting: playtesters have to be **unbiased**. On the other hand, the purpose of playtesting is not the same as the Bug Testing. When doing External QA Testing, testers do not focus on finding bugs, they just play for fun and note everything that they think it do not feel quite right in the game. So this tests are done to assure _fun quality_ is enough.

For this process, companies may follow the next template (or similar) for carrying out the playtest:

1. **Presentation** _(2 min)_

2. **Pre game questions** _(5 min)_

* Which is their favourite genre?
* Do they like or play videogames of your videogame's genre?
* ...

3. **Core playtest**

* Thinking aloud method (the tester speaks what they think while playing the game).
* The tester is observed by the test holder.
* The test holder will have minimum (or none, is possible) interaction with the tester.
* Test holder takes notes.

4. **Post game questionnaire** _(10min)_

* 1-10 Rate
* What the tester thinks about the game?
* What they would improve about the game?
* What they would keep?
* ...

5. **Thanks and send off** _(2min)_


#### Step 2: Bug Report
##### Github Issues
If your team is working with Github, an easy way of reporting bugs, crashes or glitches is using Github Issues.
This github section allows us to report bugs easily. For that, though, you might use a Bug Report Template in order to avoid chaotic explanation and to be clearer.

##### Bug Report Template
**Title:** Short and clear description of the bug. Few words as possible.

**Step By Step:** Reproduce _step by step_, as descriptive as possible, the actions that take to the bug.

**Expected Behaviour:** State what is _supposed_ to happen in the game.

**Real Behaviour:** State what _really_ happens in the game.

**Frequency:** State how often does the bug occur.
  * Always
  * High
  * Medium
  * Low

**Priority:**
  * Urgent
  * High
  * Medium
  * Low

**Version:** Version of the game the bug occurs.

![](https://github.com/VoZeS/QA-Workflow/blob/main/docs/images/bug_reports_template.png?raw=true)

##### Labels
Labels are simple tags to be putted on every bug report to easily recognise which type of it is.

**Types:**

![](https://github.com/VoZeS/QA-Workflow/blob/main/docs/images/bug_reports_labels.png?raw=true)

#### Step 3: Bug Fixing
If the bug encountered is small and it can be fixed easily, it should be done quickly and start working on the remaining features of the game once fixed. Otherwise, if the bug is big, programmers should have few more days to work on that. It should not take more than that to fix the bug. However, if that situation occurs, only the specialist in that land should focus on the bug. The other members will continue working on the project.

### QA Workflow
QA uses workflow to follow its pipeline. Workflows are very useful to know the process and how it works.

There are two levels inside the development pipeline where workflows can act. The first one reflects an external QA view, overseeing all project from the QA:

![](https://github.com/VoZeS/QA-Workflow/blob/main/docs/images/qa_workflow2.png?raw=true)

The second one reflects an internal QA view, looking inside the QA Team and how do they work, for example, for bug reporting:

![](https://github.com/VoZeS/QA-Workflow/blob/main/docs/images/qa_workflow.png?raw=true)

## Documentation
[Quality Assurance & Quality Control](https://asq.org/quality-resources/quality-assurance-vs-control)

[QA, QC & Testing](https://joshuabgad.medium.com/about-qa-in-the-game-industry-709903d780b6)

[QA Team](https://8bitplay.com/blog/ultimate-super-turbo-hd-guide-to-the-game-development-roles-qa-game-tester-jobs#what-is-QA-tester)

[General QA Info](https://github.com/cumus/Juicy_Code-Square_Up/wiki/6.-QA-Plan)

[General QA Info (2)](https://github.com/DevCrumbs/Warcraft-II/wiki/8.-QA-Plan)

[Agile](https://www.ayselucus.es/noticia/la-metodolog%C3%ADa-agile-como-herramienta-de-trabajo)

[Waterfall](https://blog.comparasoftware.com/metodologia-waterfall/)
