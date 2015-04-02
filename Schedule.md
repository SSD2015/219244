### Construction Iteration 1

#### Evaluating Usability
By end of this iteration, your application should implement these features:

1. **Login Required** - must login to view pages.
2. **Vote by Criterion** - user can vote for own contestant (project) for each criterion. There may be several criteria like "Most complete implementation", "Most creative app".
3. **Ratings** - user can assign ratings to each contestant (project). There should be a clear description of what the rating is for, and there may be more than one rating topic, such as "Playability", "User Interface".
4. **Administrative Interface** - users with admin privilege can manage contestants, voting criteria, and voting period.
5. **Compute and Display Results** - application computes "winner" for Criterion topics, and ratings (for each contestant) for Rating topics.

Based on what Aj. Panpiti said and wrote, eXceedVote should have these characteristics.

1. **Intuitive** - people can vote without any training.  App should have obvious navigation and prompts.
2. **Fast voting** - can vote quickly. Don't need to navigate a lot.
3. **Feedback and Confirmation** - user can see what he has done so far.
4. **Easy to Navigate** - easy screen should show how to get around. Never need to user browser 'back' button.
5. **Low Cognitive Load**


### Week 10 Lab
1. Quiz on using JUnit for unit testing.

### Week 9 Lab
1. Quiz on basics of Play framework. May be be paper or programming.
2. Demo EL2 work product.  TAs and instructor will choose a team member to demonstrate, so everyone should be prepared to explain and demo.
3. More unit testing.

---
### Midterm
No lab exam during midterm week.

---
### Week 8 Lab
1. Unit Testing Intro.
   * Useful intro: http://users.ece.utexas.edu/~miryung/teaching/EE461L-Spring2012/labs/testing.html
   * JUnit Home: http://junit.org JUnit is included with Eclipse and Netbeans, but it doesn't have Javadoc or other docs. Download JUnit if you want the Javadoc.
2. Unit Test Exercise. See week8/StackTesting.md for details.
3. GRASP practice.
4. Free time to work on projects.

#### Week 8 Assignment
* Prepare to demo your EL2 work product next week.
* Please study how to use JUnit and how to write test cases.

---
### Week 7 Lab
1. Each team will demo their application.
2. Discuss and submit the Design Patterns assignment from week 6.
3. Requirements update.
4. Modeling exercise (TBA).
5. Discussion of common glossary terms: Rating, Vote/Voting, "Organizer", Administrator. Many terms are being used for the contentants/entrants such as "Team", "Project", "Group".
6. Report results of your retrospective meeting to the TAs individually.
    * In the Roadmap below it lists what you should have by the end of EL1.  Check that you've done them.

#### Week 7 Assignment

* **Class Assignment:** Create consistent set of terms and definitions for concepts like (these are my terms) "Ballot Item" (something to vote or judge), "Vote", "Rate", the "contestants" or "entrants" (the things we are voting/rating), "Administrator" (make more specific).  "Organizer" is likewise _way_ too vague.
    * At eXceed Camp **who** selects the "voting" criteria and scoring method?  How is winner selected?
    * Create a common glossary for the class.
* **Add Tag**: Add a [tag](http://git-scm.com/book/en/v2/Git-Basics-Tagging) named "EL1" to mark the Github commit that **corresponds to your work products for end of EL1**.  You can use the `git tag -a` command to create a tag, or Github "releases".
    * If you've added more commits since the end of EL1, please find the commit that corresponds to your final EL1 end products and tag _that_ commit.
    * You can see your commit history on Github by clicking on "commits" button.  It shows the commit checksum prefix and commit messages; you can use the prefix as argument to the `tag` command. 
 * **Javadoc**: Write descriptive Javadoc class comments for each class and interface. Include @author tag.  Look at Java API for examples.
* Create a plan for EL2 in file _Iteration Plan for EL2.md_ on Github. Please don't abbreviate the name.
    * Include unfinished work from EL1.
* Review and update your Domain Model.
* Write fully dressed Use Cases for UC you will implement in this iteration.
* Please include these goals in EL2 if you haven't already completed them:
    1. Voter can submit his votes/ratings and system records them.
    2. System returns clear acknowledgement when votes/ratngs are received.
    3. Complete domain and software model of design to tally votes/ratings.
    4. Implement software model for tallying votes/ratings.  Provide a UI to display results.
    5. Write an Installation document (on Github) describing the steps to install and run your app.

---
### Roadmap for Next Four Weeks
We are starting Elaboration Iteration 1.  Your team will identify features to implement in EL1. To keep all teams on track, TAs and I will choose a common set of features we want all projects to implement.

By the end of EL1 you must have a running, deployable application.  You must also have good documentation, including a better set of requirements (as UC and Supplemental Requirements) and some design documentation, which you will bundle into a _Software Architecture Document_.  The SAD is for developers, so it isn't as rigorous as the SRS, but it should be accurate and complete.  Record important _design decisions_ in the SAD.  Your Web Frameworks review is a design decision.

In the next few weeks, we'll study some useful technology.  I hope to cover Unit Testing, Logging, Persistence, and a few design patterns.  We will introduce and require teams to use _Issue Tracking_ and Milestones using Github and Waffle.io, and Git _branches_ for development.

---
### Week 6 Lab
1. TA review of your progress. Be prepared to explain what you've done and what you plan to do this week (see [[Iteration Workflow]]).
2. Introduction to Design Patterns, with some (hopefully) useful patterns.

#### Week 6 Assignment
* Complete the design pattern practice exercises. Discuss & submit next week.
* Act on advice from TAs.  If they make suggestions via issues, either do them or add comment explaining why not.
* Finish iteration EL1. See _Roadmap for the Next Four Weeks_ (above) for what work products you should have.
* Have your web app running next week so you can demo it in lab.  It should be reachable from any computer in the lab via web browser.

---
### Week 5 Lab
1. Review and discussion of teams' **Domain Models**. I will choose a few teams to present, so be prepared.
  * You should be able to relate your Domain Model to your Use Cases and Mock-up.  They should be consistent.
2. (postponed) Introduction to Play! framework. 
3. Practice drawing System Sequence Diagrams.
4. Overview of Elaboration Iteration 1 (EL1), its goals, and writing an Iteration Plan for EL1.
5. Intro to issue tracking for recording tasks and progress.

#### Week 5 Assignment
* Meet with team to choose goals, tasks, and milestones for this iteration.
* Create Iteration Plan for EL1 using template. Put it on your Wiki and link to your project README file.
    * **Due:** Friday (20th) 21:00.  You may revise it later.
* Record backlog and tasks in Github as **Issues**. Record Milestones as Github Milestones (in issue tracker).
* Work on your tasks. The person doing task should "assign" it to himself (on Github), and change status as work proceeds. 
    * This is easy to do on waffle.io and it updates the issues on Github.
* Iteration EL1 ends in 2 weeks (3 March). You must have/do:
    * deployable web application
    * demo the application
    * Use Cases for EL1 written in "fully dressed" form.
    * Updated domain model, including class and sequence diagrams, _accurate_ glossary, some software design notes in SAD.

---
### Week 4 Lab
UML Sequence Diagram practice (reschedule from week3)<br>
Review of Requirements and Use Cases<br>
Domain Modeling

#### Week 4 Assignment
1. Revise and improve your Use Cases, Vision, and Mock-up.
2. Create a domain model.  You should have at least one domain class diagram and one or more sequence diagrams.  These may be sketches (don't have to be beautiful).
3. Add terms to your Glossary that explain important concept classes in domain model. For example, if you have a class named "Registrar" then explain what it is! 
4. Be prepared to explain your Domain Model in lab next week!  2-3 teams will be selected to present.

---
### Week 3 Lab
Quiz on git<br>
Meet the customer!

#### Week 3 Assignment
Each team should create a project on Github. On this site create:

1. _Vision Statement_ including Mock-up of the UI.  _Mock-up_ is not just some wishful sketch: it must show how the application will be used (screen-by-screen) and how it fulfills the customer's primary use case requirements.
2. _Glossary_ file containing terms you learned from the customer, plus any significant terms you learn from your own research.
3. _Informal Use Cases_ short descriptions of customer's requirements.  Number them UC1, UC2, etc.
4. _Supplementary Requirements_ document containing non-functional requirements, or any requirements not expressed as Use Cases.
5 _Comparison of Java Web Frameworks_: Select some frameworks, use them to create a project, and write a summary of your findings.  See: http://goo.gl/9erztx  
__Due__: Tuesday, 10 Feb, on Github.

---
### Week 2 Lab
UML Practice  
Git practice (game)

#### Week 2 Assignment
Form a team of 3-5 people for the class term project, which will begin next week.

---
### Week 1
A "mini-project" as overview of what you will do during your own software project for this course.

For today you will work in teams of 5.  You may choose a _different_ team later for the course project, so don't spend a lot of time selecting a team now.

The activities to perform are:

* Find out [[Requirements|what the customer wants]].
* Jointly develop a [[Vision Statement|Vision]] of the solution. Ask questions, draw mock-ups of what the solution will look like, investigate existing or similar projects.
* Write a [[Vision Statement]] (usually 2 pages) to guide your work.  The Vision helps keep your team on track and avoid feature creep.
* Discover requirements. In this case we will only write "user stories" or "informal use cases" that describe major features. (There are many other kinds of requirements.)
* Plan the first iteration.  What can you implement '''today'''?
* Design software for the first iteration. -- Use the whiteboards.
* Quickly write tasks you need to do.  Don't try to be complete -- you'll discover tasks as you start coding.
* Do the tasks (write the software).  Test your work!  Update your tasks, too.
* Integrate & test the result.
* Demo and review it.

#### Work Products

* Create a Github project for your team.
* In the project, write a README.md listing your team members.
* Write a short _Vision Statement_.  Vision should include:
  * Background - what is the context? what is the problem?
  * Who are the customer and stakeholders?  How does the problem affect them?
  * Why is this project worth undertaking?  (Aside from the fact that its required for this course.)
  * Your VISION of the solution.  And make it visual.  
  * How is your solution different from existing products? 
  * Write the Vision in Github or Google Docs. Put a '''link''' to it in your README.md.
  * If you use Google Docs be sure to ''share'' it.
