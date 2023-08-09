# Weekly Updates

1. What did you do last week?
2. What do you plan to do this week?
3. Are there any impedments in your way?
4. What were the processes you used last week, how can you make the process work better?

## Week 1
No reporting required

## Week 2

1. What did you do last week?
    - Read all the course descriptions and requirements
    - Coded and posted web pages on github
    - Wrote questions and responded on piazza
    - Drafted a project proposal
    - Read background materials for proposal 
2. What do you plan to do this week?
    - Refine proposal, post, get comments feedback
    - Identify resources materials, online, textbooks etc.
    - Read more background materials to identify potential stumbling blocks
    - Develop reading list for coming weeks to sync tasks with new knowledge
3. Are there any impediments in your way?
    - Summer!   Really, summer requires extra attention to putting in the time required.  Keeping a good tempo will be important
4. What were the processes you used last week, how can you make the process work better? 
    -   I reviewed the requirements and made a list of tasks, which was a bit iterative.  One of the mistakes I always make in CSPB courses is not looking ahead to next week’s assignments, before making up a workplan.  Often the following week's task or description provides important information relevant to the current week's work.  Be tactical and strategic, look ahead.

## Week 3

1. What did you do last week?
    - Finalized proposal
    - Developed work schedule
    - Downloaded and read PyQt books (4 chapters)
    - Downloaded and started to read OOP documentation
    - Wrote first PyQt code to create dialogue box
    - Fixed up git website (added Jekyll config file)
2. What do you plan to do this week?
    - Plan application layout
    - Consider open-source issues (what will make my app attractive for others to use\contribute)
    - Develop main screen for application
    - Keep reading PytQt documentation
    - Look at linked-in
3. Are there any impediments in your way?
    - Main issue is time.  Being Summer and my son is in day camp, I have short days to work with.  
4. What were the processes you used last week; how can you make the process work better? 
    -   Setting a work agenda is key, as it allows me to just sit down and start working, not wonder first about what I must do.  
    -   Make setting weekly work agenda on Monday priority (this is rather detailed list)
    -   Check the agenda again on Wednesday (in most cases I can add to it)

## Week 4

1. What did you do last week?
    - Read PyQT (3 chapters)
    - Started repo for my program files
    - Started reading OOP
    - Finshed app layout (this will be modified as I go along, but it is a broad brush to keep focused)
    - Developed main screen for application
    - Continue to improve github web site 
2. What do you plan to do this week?
    - Finish first tab to read in database location and specifications
    - Develop methods for saving settings from one session to the other (use PyQt Settings class)
    - Start second tab for sectors (work on PyQt data API)    
    - Work on linked-in
3. Are there any impediments in your way?
    - Reading and working on code is a great combo, theory and applications work well for me, but application often requires more th
    - en just theory, it require experience. 
4. What were the processes you used last week; how can you make the process work better? 
    -   Setting a work agenda is key, as it allows me to just sit down and start working, not wonder first about what I must do.  
    -   Get more reading in at odd hours (down time) by having it on mulitple computers synched up
   
## Week 5

1. What did you do last week?
    - First tab done, reads in data location and verifies if database is valid, returns an error box if not valid
    - Integrated method for saving users state between session using PyQt Setting Class
    - Started sectors tab (tab 2) by creating layout (vlayout and hlayout, with buttons)
    - Read up on best practices to create a linked in site, talked to friends who have done it about pros and cons
3. What do you plan to do this week?
    - Continue to develop second tab for sectors (this tab will be used as a template for other tabs, so want to get it right)
    - Develop code to make tasks for user more efficient (painting data, quick selection)
    - Review options for saving application data (for datafiles in contrast to user settings)
        - SQLite
        - Json
    - Continue to work on linked-in
4. Are there any impediments in your way?
    - None 
5. What were the processes you used last week; how can you make the process work better?
    - Working with Qt documentation helps a lot, essential.  Qt documentation is written in C++, not python.  Getting to know the structure of objects within Qt and inheritances, along with enums is essential.  It takes time to look up all the options and configurations with the enums.
    - Solution: study the overall object structure and inheritance hierarchy within Qt so I can access required information more efficiently.
  
## Week 6
1. What did you do last week?
    - Studied data structure for data persistence between sessions (MySQLite or Json data formats)
    - Decided to use Json, since it can store lists and dictionaries in an easy to access structure
    - Many of my tasks will be manipulating lists, so putting and extra level of abstraction in the form of SQL added unneeded complexity 
    - Worked on creating an initial data structure in the form of a Json file with data (dictionaries and lists (these default templates required a lot of custom data to start off the program      
2. What do you plan to do this week?
    - Now that I have decided on a data structure to persist data, and the default file is setup, I need to integrate the Json data into the interface (now, I have some lists shoehorned into the model in place of a data structure.
    - Integrating the data model will require careful placement within the interface to leverage object inheritance and reduce duplication and unneeded read and writes.  
3. Are there any impediments in your way?
      - Yes.  Experience with OOP, inheritance, signals, and slots.  It is one thing to study this material and understand how it is implemented, it is another thing to implement a structure which serves the purpose well.  I must dive in a try my best idea and see how it plays out (learn the pros and cons of my approach).
4.  What were the processes you used last week; how can you make the process work better?
   - The process has changed entirely.  I have gone from studying PyQt documentation to planning strategy around various programming structures to achieve my goals.  This is planning and implementation, so the processes are different.  I consider, look at existing code, and adapt as needed, while anticipating potential problems.

## Week 7

1. What did you do last week?
    - Coded a class object to hold data and processes it.
    - Used PyQt Signals and Slots to create connections to events which change the data in the data object (changing data directory or changing aggregation file).
    - Read in JSON file and sets file, merge them by codes using a dictionary and list structure which is efficient (essentially a hash index with a merge).
    - Passed data to the tab "by reference" which means when the data in the application tables changes, the data in the data object will also be changed, reducing unneeded code and improving efficiency.
    - Tested code on sectors tab.
2. What do you plan to do this week?
    - Cleanup class object code, with properties and setters and getters as required.
    - Develop an interface and code to "save" a new data object and retrieve it.
3. Are there any impediments in your way?
      - No.  
4. What were the processes you used last week; how can you make the process work better?
   - I studied the code a great deal to figure out where to put the data object and how best to apply it before I started coding.
   - In the future I will create a sandbox to test ideas sooner, with less concern on getting it correct the first time, since I found I spent several hours simply studying the code and considering options.  While that worked, it seemed a bit time consuming.

## Week 8

1. What did you do last week?
   - Cleaned up the dataStore class object - this required inserting more code to account for various user interactions
   - Signals and slots were added so that the dataStore object behaved as expected (previous version required a restart of app when database was changed)
   - Added a lot of setters and getters - read up on various methods of doing setters and getters in Python and all their pros and cons (hint, using a lot of properties and setters is not always the best if you intend on reusing a class with inheritance.
   - Most of all I tested methods for passing data to the "view" tabs and updating the user screens.  This project is a mix of data science and user interface (software engineering).  These methods will be used to support the next round of development (saving and retrieving user data schemas).
   
2. What do you plan to do this week?
   -Develop the saving and retrievalof user data schemas.  Had hoped to have done that last week, but I had to explore how best to do this first.  Now I know the method I plan to use, 
3. Are there any impediments in your way?
   -Main challenge has been integrating the GUI code with the data objects I have created to save and retrieve data.  I have good ideas and have made good progress on both the GUI code and the database object code.  However, integrating the two has been an unexpected challenge, requiring a much deeper understanding and planning with both to make them interact consistently for the user
     
4. What were the processes you used last week; how can you make the process work better?
   - before developing a bunch of setters and getters, I read up on the web about these in Python.  I could have done it without reading.  However, understanding how they work under the hood in Python was helpful, if only for future development.  As it turns out, setters and getters are rather static in Python as they relate to OOP inheritance - one can't morph the setters and getters as we do with other code using super().  That is an important restriction.
   - When I ran into the "big" challenge of integrating my data object with the GUI objects, I decided to perform some simple experiments with my code, before diving in with writing a lot of code.  I branched the code to create a sandbox.  I then picked some simple code areas and tried to pass the data along.  I had planned to use Python references to avoid duplication of data (passing by reference).  I had problems.  I then used the Python id() functions to see why the data were not being passed by reference.  Turns out, they were, as I had planned, however, this method did not trigger the "view" screens to update! Passing the data by value forced the view objects to update.  That was the desired outcome.  I could have come up with other methods to force an update of the view screen, but there are tradeoffs, not the least, the code would get very complicated.
   - This method of taking a small problem and working out the kinks was far superior then starting out with the big project.
   - In many ways, I have kept the GUI simple to this point, working out a lot of the underlying methods, then I will build out more efficiently
   - The processes work best, and can work better, but strategically testing ideas and methods on small chunks.  DO NOT ASSUME the interaction of the different pieces of code will be straight forward.

# Mid-semester Project Update

1.  Goals
   * Create GUI interface which gathers input from users
   * Input from users is checked, stored in MySql and passed to external programs (Fortran)
   * Progress bar for running programs (they can take a while to run)
   * Information on status (completion) of each task)
   * Learning OOP
   * Advanced Goal - Multithread 
2.  Assessment
   * Create GUI - Achieved this goal, making the GUI was mostly about reading documentation and books and trying it out.  Working with PyQt documentation was initially intimidating, since it is all organized by object trees and written for C++.  However, after a few weeks of referencing the documentation, I believe I have become proficient at finding what I need and implementing it.
   * Input from user and stored in MySQL - This was really two tasks.  Input from user done, with several customized features to facilitate data entry (painting value, spreadsheet like copy and paste via a customized delegate).  
Dropped the MySQL idea. Upon considering the tasks of the GUI, I decided that using native Python data structures (lists and dictionaries) wouldg be better suited to the application.  The data were better represented in an unstructured database.  Data are persisted in JSON format.
   * Progress bar for running programs-(TBD, have read up on the tools)
   * Learning OOP – I have read Part IV in Mark Lutz “Learning Python” on OOP.  OOP knowledge is essential for working with PyQt, which is based on object hierarchies.  Reading with an application in OOP has worked well for learning.
   * Advanced goal – I have read the chapters in PyQt on multithreaded applications.
3.  Updated goals
   * Though this is midway through, I don’t feel ready to update goals.  I’m sure I don’t want to add any new goals to the list I have.  Looking at the progress I have made, in terms of the application interface, the interface is only about 25% done.  That is less than 50%.  However, my experience with this project is that developing an application is uneven in its progress.  Sometimes it moves fast, sometimes one must invest time to develop tools to be efficient.  I have built a lot of tools for my application.  I have nearly completed the most difficult parts of the application and created several objects which will be used with small modifications (inheritance and polymorphism) to complete the next 50% of the project. The next week of work will determine the status of the project and then I will adjust goals.

# Professional Development Review

As per the class assignment, I have investigated professional development tools for future use.  I found career fairs to be particularly interesting, since they are essential networking opportunities.  I signed up for the CU career fair network (handshake), to see what it contained.  While it did not provide any specifics on career fairs, it did ask a lot of interesting questions that go to "what are you doing with your career?".  Next, I tried the resume evaluator (VMOCK). I was  interested to see what it came up with for me.  I have a long resume and a lot of accomplishments, but my resume is a consulting resume, meant to be tucked into the back of a proposal, so clients can see all the great things we have done.  They are decidedly not formatted for "career search".  So I wanted to see what it said.  It said that while my resume lacked a lot of proper active voice\tense, it hit all the marks on things recruiters are looking for: leadership, communication, teamwork, initiative, and analytics.  I think I can use that advice and improve my consulting resume.  

Finally, I signed up for, and watched, a video in the linked in learning area.  I watched a video on time management, as suggested.  The video reminded me of many tools I do use (I'm a focused person).  I want to watch some of the other videos on programming, will make the 30 minutes a week available as the time management video suggested.  Overall, a great review of lifelong learning tools.  It’s a reminder that at all stages of our work life and careers, we should make these regular habits since they enhance out self-worth in our work life.

## Week 9

1. What did you do last week?
   - Continued to revise the data schema and data object for collecting, storing and saving user data in a consistent fashion
   - Added several signals and slots to coordinate transfer of data between user screens and data objects.
   - Completed the Open and Save features in the interface (as expected, these were relatively easy, given a consistent and robust data and interface)
   - Added quit menu button to leave the app
   - Add an about screen to list credits and contact information
   - Watched Linked in Learning Video on OOP in Python
     
2. What do you plan to do this week?
   - Develop new tab for regions (this should go fast and without trouble, since it will use all the objects already created and tested
   - Develop new tab for endowments (again, this should be straight forward extension of what has been done, though I will need to modify the tab a bit)
   - Start work on output programs (these should be familiar, since I already know how to write python scripts for file and program execution)
  
3. Are there any impediments in your way?
   - I feel comfortable with the state of the objects I have built, and hope things will move more quickly now that a solid foundation is set up.
     
4. What were the processes you used last week; how can you make the process work better?
   - As with the previous week, I reviewed materials on OOP to see if anything there could help (some did, but mostly in organization)
   - I branched a set of code to "play" and experiment with things, without fear of destroying previous work, to test ideas.
   - I could make these processes better by allowing more time to play and fully explore the ideas.  Sometimes I have the correct idea, but there is something in the implementation that keeps it from working the way I expect (i.e., passing values by assignment in Python).  I could, therefore, end up missing on a good idea and knowledge development for the wrong reasons.  Planning a solid exploration is better than quick code tests.
  
5. Updated work plan to end of semester
	- Week 10 - Continue to develop tabs
	- Week 11 - Finish output tab
	- week 12 - Clean up code
	- Week 13 – Document on GitHub, add video (?)
## Week 10

1. What did you do last week?
   - Built regions tab for user input - based the tab off the sector tab
   - Built the endowments tab for user input - required a sub-class of the regions tab with a few modifications for the unique input of this data
   - Started work on output tab, which requires a number of operating system routines I have used separately.  However, they will have to be modified to work within the GUI structure.
     
2. What do you plan to do this week?
    - Finish the output tab and its routines
    - Debug program to get this version reasonably stable (have been testing along the way)
    - Start working on wrap up of project
  
3. Are there any impediments in your way?
   - No (maybe a camping trip?) 
     
4. What were the processes you used last week; how can you make the process work better?
   - This week was all about reusing the previous materials (objects) I created earlier, so the effort of getting those in a stable working environment has been paying off
   - I took some risks investing in the basic tab and data objects and getting them general enough that they could be reused with small modifications and all the data could be quickly and efficiently saved.  That has paid off well.
   - I am now looking at the objects and their use and I can see some redundancy in how the code is now fleshing out.   I have convinced myself; some redundancy is OK and can be cleaned up later with some refactoring of the code.  There is a time to build and invest and then there is a time for things to develop in the context of use and learning. I'm happy where the code is at, more improvements will always be possible.

## Week 11

1. What did you do last week?
   - Finished the output tab
   - Debugged the system by testing, testing, testing
   - Integrated a multithreaded procedure to run 8 programs at once
   - Developed a progress gauge for the output tab
     
2. What do you plan to do this week?
   - Wrap up the project to a finished state
   - Write up accomplishments
   - Work on GitHub settings and web page for the application
  
3. Are there any impediments in your way?
   - Using the GitHub interface is sometimes a mystery to me, I will have to find resources to guide me
     
4. What were the processes you used last week; how can you make the process work better?
   - I spent a lot of time debugging and working through code to find problems
   - I can make that process better by making sure I have a solid test case, with data and structures I know work, so I'm not debugging the code and the data at the same time.


## Week 12

1. What did you do last week?
   - Cleaned up a bit of code and pushed it to the GitHub repo
   - Researched GitHub open-source repos and the common usages
   	- Watched linked-in learning on setting up GitHub repo
   	- Read several documents on managing pull requests
   	- Read up on process of forking a repo (required for someone who wants to contribute)
   	- Read up on setting to protect branches
   - Set branch protections for main
   - Deleted old branches
   - Started an issue tracking log
   - Updated project pictures on my wiki (https://github.com/pedrocu/pedrocu.github.io/blob/main/docs/progress_pics.md)
2. What do you plan to do this week?
   - Work on final project write up
   - Develop readme.md file on GitHub for repo
3. Are there any impediments in your way?
   - No
4. What were the processes you used last week; how can you make the process work better?
   - Last week was a strategic dive into coding and getting the project working, that worked fine
   - This week is a shift to the big picture, beyond the code, making sure GitHub is setup and that I understand how to work an open-source project.
   - Also working on documentation of where I am at to continue work.


